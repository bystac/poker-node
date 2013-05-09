higly scalable poker server

the application will separated to 2 parts:
- Game services
- Backoffice

__Game services__

Only server side will be implemented, the client side can should be implemented by others.
TODO: provide basic skeleton for poker client.

All services will work with push over sockets
- Authentication
- Accounting
- Lobby
- Tables


__Backoffice__ 

to be determined, I really don't care about this, not intresting topics.

__Databases/Storage__ 

My first though wa *yeah lets use mongodb* but then I rethink we have to have ACID, so MariaDB or PostgreSQL better 
suited, in front of them ti handlle all the traffic and events I'll be using the great Redis.


__Question to think about__
* language support?
* currency support?
* Play money? real money? switch?
