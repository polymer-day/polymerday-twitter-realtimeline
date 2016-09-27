# \<polymer-twitter-realtimeline\>

Twitter real timeline. It will track a 'active' hashtag from firebase

**IMPORTANT**: In order to this web component works, the server side api (in other repo) needs to be up and running

```html
<polymer-twitter-realtimeline
            api-url-base="[[apiUrlBase]]"
            ...
            ...></polymer-twitter-realtimeline>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Firebase
You will need to create and set up a [Firebase Realtime Database](https://firebase.google.com/docs/database/) 
and in demo index file configure the firebase-app component

```html
<firebase-app
          auth-domain="your_your_auth_domain"
          database-url="your_data_url"
          api-key="your_api_key"
          storage-bucket="your_storage_bucket"></firebase-app>
```
The database mush have a path, you can change it in demo code. By default (active/hashtag/to/track)

![path](https://cloud.githubusercontent.com/assets/10350688/18666822/1b2f229e-7f2e-11e6-947c-40214ea45330.png)


## Viewing Your Application and Demo

```
$ bower install
$ polymer serve
```

Take a look at demo code to know how to use the web component
