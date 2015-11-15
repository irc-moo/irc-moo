# backend architecture
The backend is composed of 3 services.

# irc service
The irc service is in charge of abstracting the connection between client and the real irc servers. We need to do this for the following reasons:

* Connect to the irc network from a browser, browsers don't support TCP.

* Capture incoming and outgoing client messages, for log keeping.

#### stack
* node (lang/framework)

#### load balancing
Undecided, but we will need to support sticky sessions.

#### deployment
AWS code deploy

#### hosting
AWS EC2

# rest service

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

# db service
The db will store user objects and irc logs. A big requirement is for the irc logs to be efficiently searchable, luckily, postgress supports this out of the box however scaling is still unknown.

#### stack
* postgress (DB)

#### load balancing
Undecided

#### deployment
Undecided

#### hosting
Undecided
