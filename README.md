# organizy [concept]

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/organizy-chat/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
[![license](https://img.shields.io/github/license/organizy/documentation.svg)]()

[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/organizy/documentation.svg)](https://github.com/organizy/documentation/pulls?q=is%3Apr+is%3Aclosed)
[![GitHub contributors](https://img.shields.io/github/contributors/organizy/documentation.svg)](https://github.com/organizy/documentation/graphs/contributors)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/organizy/documentation.svg)](https://github.com/organizy/documentation/issues?q=is%3Aissue+is%3Aclosed)

[![GitHub pull requests](https://img.shields.io/github/issues-pr/organizy/documentation.svg)](https://github.com/organizy/documentation/pulls)
[![GitHub issues](https://img.shields.io/github/issues/organizy/documentation.svg)](https://github.com/organizy/documentation/issues)

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

Nemanja Nedeljković
