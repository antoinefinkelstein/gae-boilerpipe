# About
Simple implementation of [modified Boilerpipe HTML extractor (with images)](http://github.com/gregbayer/boilerpipe) for Google AppEngine.

It consists of a single servlet that takes a url parameter and returns Boilerpipe extracted HTML including images.

[http://<boilerpipetestapp>.appspot.com/boilerpipe_parser?url=<url>](http://<boilerpipetestapp>.appspot.com/boilerpipe_parser?url=<url>) 

# Setup

* Replace all instances of <boilerpipetestapp> with your GAE application name
* Replace <url> with the url you would like to parse