# higly scalable poker server


The application will separated to 2 parts:
- Game services
- Backoffice

## Game services

Only server side will be implemented, the client side can should be implemented by others.
TODO: provide basic skeleton for poker client.

All services will work with push over sockets
- Authentication
- Accounting
- Lobby
- Tables


## Backoffice 

to be determined, I really don't care about this, not intresting topics.

## Databases/Storage

My first though wa *yeah lets use mongodb* but then I rethink we have to have ACID, so MariaDB or PostgreSQL better 
suited, in front of them. To handlle all the traffic and events I'll be using the great Redis storage.


## Question to think about
* language support?
* currency support?
* Play money? real money? switch account?
