# CustomerService

Source of truth for Customer data. Provides API to access and manipulate 
customers data.

Owner|Tier|Status|Contexts
---|---|---|---
CommunicationsTeam|Tier1|Prod|Web,Customers

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

Staging:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://... 

##### Tech

- Golang 13.x: implementation
- AWS ECS: execution env
- AWS ALB: request routing
- AWS SNS: domain events transport

