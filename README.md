tweetly.js
==========

A Node.js command-line Twitter client.

Install
-------

Issue the following command to install:

    $ npm install -g tweetly.js

Configure
--------

Tweetly.js will authenticate on the first run:

    $ tweet
    
    Launch your browser and point it to:

    https://api.twitter.com/oauth/authorize?oauth_token=SJwXLWJIXXXXXXXXXXX

    Then return here, paste the pin number, and hit enter.

Once you do that, it'll save your oauth token in `./.tweetlykey`


Usage
-----

Tweet using the following format:

    $ tweet 'Hey Twittersphere!'

(Make sure to use single quotes)

Authenticate With a New User
----------------------------

Simple remove `./.tweetlykey` and run tweetly.js again.

    $ rm .tweetlykey
    $ tweet