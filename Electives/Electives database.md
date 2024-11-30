---

database-plugin: basic

---

```yaml:dbfolder
name: new database
description: new description
columns:
  __file__:
    key: __file__
    id: __file__
    input: markdown
    label: File
    accessorKey: __file__
    isMetadata: true
    skipPersist: false
    isDragDisabled: false
    csvCandidate: true
    position: 1
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: true
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  __tags__:
    key: __tags__
    id: __tags__
    input: metadata_tags
    label: File Tags
    accessorKey: __tags__
    isMetadata: true
    isDragDisabled: false
    skipPersist: false
    csvCandidate: false
    position: 2
    isHidden: true
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  State:
    input: select
    accessorKey: State
    key: State
    id: State
    label: State
    position: 4
    skipPersist: false
    isHidden: false
    sortIndex: -1
    options:
      - { label: "New York", value: "New York", color: "hsl(34, 95%, 90%)"}
      - { label: "Maryland", value: "Maryland", color: "hsl(359, 95%, 90%)"}
      - { label: "Alabama", value: "Alabama", color: "hsl(251, 95%, 90%)"}
      - { label: "Ohio", value: "Ohio", color: "hsl(154, 95%, 90%)"}
      - { label: "Georgia", value: "Georgia", color: "hsl(28, 95%, 90%)"}
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      option_source: manual
  Eligible:
    input: checkbox
    accessorKey: Eligible
    key: Eligible
    id: Eligible
    label: Eligible
    position: 5
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  City:
    input: text
    accessorKey: City
    key: City
    id: City
    label: City
    position: 6
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  App_Deadline:
    input: calendar
    accessorKey: App_Deadline
    key: App_Deadline
    id: App_Deadline
    label: App_Deadline
    position: 7
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Webpage:
    input: text
    accessorKey: Webpage
    key: Webpage
    id: Webpage
    label: Webpage
    position: 8
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  App_Fee:
    input: number
    accessorKey: App_Fee
    key: App_Fee
    id: App_Fee
    label: App_Fee
    position: 9
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Elective_Fee:
    input: number
    accessorKey: Elective_Fee
    key: Elective_Fee
    id: Elective_Fee
    label: Elective_Fee
    position: 10
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Doccuments_Required:
    input: text
    accessorKey: Doccuments_Required
    key: Doccuments_Required
    id: Doccuments_Required
    label: Doccuments_Required
    position: 11
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 240
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: true
  Rotations:
    input: text
    accessorKey: Rotations
    key: Rotations
    id: Rotations
    label: Rotations
    position: 12
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 242
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
      wrap_content: false
  Available_Dates_start:
    input: calendar
    accessorKey: Available_Dates_start
    key: Available_Dates_start
    id: Available_Dates_start
    label: Available Dates start
    position: 13
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 127
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  Available_Dates_End:
    input: calendar
    accessorKey: Available_Dates_End
    key: Available_Dates_End
    id: Available_Dates_End
    label: Available Dates End
    position: 14
    skipPersist: false
    isHidden: false
    sortIndex: -1
    width: 122
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
  newColumn13:
    input: text
    accessorKey: newColumn13
    key: newColumn13
    id: newColumn13
    label: Notes
    position: 3
    skipPersist: false
    isHidden: false
    sortIndex: -1
    config:
      enable_media_view: true
      link_alias_enabled: true
      media_width: 100
      media_height: 100
      isInline: false
      task_hide_completed: true
      footer_type: none
      persist_changes: false
config:
  remove_field_when_delete_column: false
  cell_size: normal
  sticky_first_column: false
  group_folder_column: 
  remove_empty_folders: false
  automatically_group_files: false
  hoist_files_with_empty_attributes: true
  show_metadata_created: false
  show_metadata_modified: false
  show_metadata_tasks: false
  show_metadata_inlinks: false
  show_metadata_outlinks: false
  show_metadata_tags: true
  source_data: current_folder
  source_form_result: 
  source_destination_path: /
  row_templates_folder: /
  current_row_template: Electives/John Hopkins.md
  pagination_size: 10
  font_size: 12
  enable_js_formulas: false
  formula_folder_path: /
  inline_default: false
  inline_new_position: last_field
  date_format: MM-dd-yyyy
  datetime_format: "MM-dd-yyyy HH:mm:ss"
  metadata_date_format: "MM-dd-yyyy HH:mm:ss"
  enable_footer: false
  implementation: default
filters:
  enabled: false
  conditions:
```