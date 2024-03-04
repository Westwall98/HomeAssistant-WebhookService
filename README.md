### Manual Setup
Copy all the files in `custom_components\webhook_service` to `custom_components\webhook_service` in your HomeAssistant.

## Configuration
Simply add `webhook_service:` to your configuration.yaml file

## Usage
Use the `webhook_service:basic_webhook` service in automations to post json data to a webhook

```
service: webhook_service.basic_webhook
data:
  webhook: https://somewhere.com
  json: {"test": "test"}
```
