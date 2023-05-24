<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| application | Application name | N/A | true |
| cluster | Cluster name | N/A | true |
| debug | Debug mode | false | false |
| ecspresso-version | Ecspresso version | v2.1.0 | false |
| image | Docker image | N/A | true |
| image-tag | Docker image tag | N/A | true |
| overrides | A list of container overrides in JSON format that specify the name of a container in the specified task definition and the overrides it should receive. | {} | false |
| region | AWS Region | N/A | true |
| taskdef-path | Task definition path | N/A | true |
| timeout | Ecspresso timeout | 5m | false |


## Outputs

| Name | Description |
|------|-------------|
| webapp-url | Web Application url |
<!-- markdownlint-restore -->
