# organizy [concept]

Idea behind it is to make powerfull event driven automation like IFTTT, but, opensource, scalable, distributed and programmable. 

## Workers

Workers are core components of organizy and their main goal is to pass events between components. 

## Components

Component is anything that uses organizy protocol. 

## Event system

Event system is IRC like enviroment where components are able to hook into channels and broadcast into them. 

All events are broadcasted using webhooks or websockets. 

### Clock event

There is clock event that is broadcasting events once each second, minute, hour... 

### WebHook event

Components are broadcasting events using webhooks. 

## Todo

 - [x] Write bootstrap documentation
 - [ ] Write regy
 - [ ] Write gety
 - [ ] Write sendy
 - [ ] Unknown plans

## Author

Nemanja Nedeljkovic

