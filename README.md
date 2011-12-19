tweetly.js
==========

A Node.js command-line Twitter client.


Usage
-----

Tweet using the following format:

    $ tweet 'Hey Twittersphere!'

(Make sure to use single quotes)


Install
-------

Issue the following command to install:

    $ npm install -g tweetly.js


Configure
--------

Tweetly.js will authenticate on the first run:

    $ tweet
    
    Now launching your browser and pointing it to:

    https://api.twitter.com/oauth/authorize?oauth_token=SJwXLWJIXXXXXXXXXXX

    When you finish, return here, paste the pin number, and hit enter.

Once you do that, it'll save your oauth token in `~/.tweetlykey`.


Authenticate With a New User
----------------------------

Simply remove `~/.tweetlykey` and run tweetly.js again.

    $ rm ~/.tweetlykey
    $ tweet


License
-------

Copyright (c) 2011 Kyle Fleming, released under the MIT license:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
