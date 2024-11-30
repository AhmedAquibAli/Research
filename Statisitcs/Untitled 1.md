```r
#| label: 5feceb66
library(survival)

library(ggplot2)

library(ggpubr)

library(survminer) # For enhanced plotting capabilities

# Sample data: Time to event (time), event indicator (status) and group

# status = 1 indicates event occurred, 0 indicates censored

data <- data.frame(

time = c(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 1, 3, 5, 7, 9, 2, 4, 6, 8, 10),

status = c(1, 1, 1, 0, 1, 1, 0, 1, 0, 1, 1, 0, 1, 1, 0, 0, 1, 0, 1, 0),

group = factor(rep(c("A", "B"), each = 10))

)

# Create the Kaplan-Meier object

fit <- survfit(Surv(time, status) ~ group, data = data)

  

# Plot the Kaplan-Meier curves using survminer for better aesthetics

ggsurvplot(fit,

data = data,

palette = c("#E7B800", "#2E9FDF"), # Customize colors

risk.table = TRUE, # Add risk table

risk.table.col = "strata", # Color risk table by group

legend = "bottom", # Legend position

legend.title = "Group", # Legend title

xlab = "Time", # X-axis label

ylab = "Survival Probability", # Y-axis label

title = "Kaplan-Meier Survival Curves", #Main title

ggtheme = theme_bw() #Use a black and white theme
)
```
