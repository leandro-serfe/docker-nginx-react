# Docker React Nginx

This is an starter kit for React applications

## Pre-requisites

You need *docker* and *docker-compose*

## Usage

Clone this repo and then add or edit your *git remote* to point to your project repository

### Get your app running
```
docker-compose up
```

Then go to [http://localhost:3000/](http://localhost:3000/)

### Run build
```
docker-compose run node yarn build
```

### Deploy staging
You can use Nginx to deploy an stage app

### React Native
You can also use this for ReactNative when you are sharing components with a Web app.

Recommended folder structure for sharing components

```
app/
  |--/mobile/ # add here only mobile components
  |--/pub
      |--/web
           |--/static
      |--/mobile
           |--/assets
  |--/web/ # add here only web components
  |--/shared/ # add here all shared components
  |--/layouts/
  |--/views/
      |--/mobile/
      |--/web/
```
