# HRGotchi
Live class pet for Hack Reactor.

<img src="./examples/hrgotchi_desktop.png">

## Team

  - __Product Owner__: [Emmeline Lan](https://github.com/bloodymushroom)
  - __Scrum Master__: [Lisa Nam](https://github.com/lisanam)
  - __Development Team Members__: [Don Nguyen](https://github.com/nguyendkim), [Lisa Nam](https://github.com/lisanam), [Emmeline Lan](https://github.com/bloodymushroom), [Haris Muhammad](https://github.com/harismh)

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#Requirements)
1. [Installing Dependencies](#Setup)

## Usage
To see pet, visit:


```
localhost:3000
```


Adjust live polling:

In `server.js` set `setInterval(poll, 5000);` to desired interval.

Test polling:

Send `GET` request to `/api/test`

## Requirements

- Node
- Bower
- MySQL


## Setup

Initialize database:


```
mysql -u root -p

create database hrgotchi;

use hrgotchi;

INSERT into Pets (name) VALUES ('CHOOSE_NAME');
```


From within the root directory:


```
npm install

cd public

npm install && bower install

```


Start SQL:


```
mysql.server start
```


Compile React:


``` 
npm run startReact 
```


Start Server:


```
npm start 
```

Visit:


```
localhost:3000
```

## Roadmap

View the project roadmap [here](https://github.com/Sagacious-Sycamore/Sagacious_Sycamore/issues)
