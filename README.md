![logo](https://github.com/user-attachments/assets/0d41b803-968a-41a8-809a-0dd3d91ec489)

Base URL: https://api.trackmyuser.com

## 1. S2S Events Request

Endpoint: POST /v1/measurement/event/s2s/create

Request Body:

Example Request:

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
