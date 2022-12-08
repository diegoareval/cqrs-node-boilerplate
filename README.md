# Node js app applying cqrs
## Node js + Typescript + Redis + Mongo + CQRS

### Description: 
CQRS it is a way to split queries and commands (Command Query Responsibility Segregation)
- src/config: indicates the setup of mongo and redis
- src/app: contains the main routes where all the routes are interconected and also the event handler this item help to orchestrate all the events that is gonna be triggered
- src/students: it is related with the module itself
- src/students/models: it returns the models to query or execute the commands to interact with the db instance

app -> routes => controller -> module command -> event handler => event module

![CQRS FLOW](cqrs.png)
