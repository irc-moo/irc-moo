# backend architecture
The backend is composed of 3 services.

## irc service
---
The irc service will be encharged of abstracting connections between client the irc servers this allows us to connect to the irc network from a browser, since browsers don't support TCP. This is also necessary to capture imcoming and outgoing messages for log keeping.

#### stack
* node (lang/framework)

#### load balancing
undecided, but we will need to support sticky sessions for two reasons:

#### deployment
AWS code deploy

#### hosting
AWS EC2

## rest service
---

The rest service will be a

#### stack
* node (lang/framework)
* hapi (HTTP lib)
* sequelize (ORM)

#### load balancing
AWS EBS

#### deployment
AWS code deploy

#### hosting
AWS EC2


## db service
---
The db will store user objects and irc logs. A big requirement is for the irc logs to be efficiently searchable, luckily, postgress supports this out of the box however scalling is still unknown.

#### stack
* postgress (DB)

#### load balancing
unknown

#### deployment
unknown

#### hosting
unknown
