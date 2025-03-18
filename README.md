![logo](https://github.com/user-attachments/assets/0d41b803-968a-41a8-809a-0dd3d91ec489)

## 

```perl
https://api.trackmyuser.com
```

## 1. S2S Event Request

### Overview

The endpoint is used to ingest events from your server.

### Endpoint: 

```perl
POST /v1/measurement/event/s2s/create
```

### Request Paramerters

| Parameter   | DataType | Summary  |
|--------|----:|---------|
| app_token  |  String | Your app's SDK token      |
| s2s_key    |  String | The token used to authenticate your request  |
| user_id|  String | User ID set by the SDK      |
| event_code|  String | The code of the event created in the dashboard      |
| revenue_value|  Float |  Revenue value of the event      |
| revenue_currency|  String | ISO 4217 alphabetic representation of the curreny     |


### Example Request Body

```json
{
  "app_token": "A4CAB7AC-6ED3-4B8E-8E11-BC3FA4D66C65",
  "s2s_key": "AEB865BB-A6BE-4852-B548-B84201F01E5F",
  "user_id": "6DF4F2E1-DCE6-4A16-B566-46247F5FC027",
  "event_code": "PURCHASE",
  "revenue_currency": "USD",
  "revenue_value": "2.06" 
}
```
