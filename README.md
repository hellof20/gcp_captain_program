# gcp_captain_program

## Prerequisites
Enable Security Command Center Preminum Level

## Create custom module
- custom module for project
```
gcloud scc custom-modules sha create --project=projects/your_project_id \
  --display-name=your_module_name \
  --enablement-state="ENABLED" \
  --custom-config-from-file=module_yaml_file_name
```

- custom module for org
```
gcloud scc custom-modules sha create --organization=organizations/your_org_id \
  --display-name=your_module_name \
  --enablement-state="ENABLED" \
  --custom-config-from-file=module_yaml_file_name
```
