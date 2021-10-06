
# Meeting notes
## 2021-10-06 08:59

## People
[[Elmira Ahmedova]]
[[Jack Contro]]
[[Rik Watson]]

## Notes
### Logging
The app says "This event has happened"
Frontend <-> Backend communications through GraphQL

At moment no logging at the frontend - you can't trust the frontend. You can't trust the browsers (end users can do something weird)

We need to start by logging at the GraphQL point.
We are using AWS -> use Cloudwatch as their made logging service 
Inject into cloudwatch the info

### Monitoring 
Start to consider the state of things
Is the Kubernetes doing ok? 

### Alerting
Connected

## Outcomes
Start with working on GraphQL logging


## Personal Todos
introduce Elmira to graphql and backend
Introduce to boto3
lucidchart
branching policy
tickets

#### tags

#meeting