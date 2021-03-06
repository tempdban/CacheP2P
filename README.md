<h1 align="center">
  <br>
  <br>
  CacheP2P
  <br>
  <br>
</h1>

<br>

**CacheP2P** is a highly distributed [cache](https://en.wikipedia.org/wiki/Cache_(computing)) platform based on [WebTorrent](https://webtorrent.io/) and runs only in the **browser**.

It is a javascript library that once included in a website, makes every new user a mirror of the specific URL he has opened and allows it to serve it to all the other users that also are accessing the same website, so the website's server doesn't have to. 

This way users can share the content between themselves, reducing the number of requests for estatic content to the server.

If the website crashes or has problems (the script can be included in the server's error page), all the content that users were accessing in that moment can be retrieved from one another and as long as there are users accessing it no problem will be seen.

For more information, please read the [documentation](http://www.cachep2p.com/documentation.html) or [how it works](http://www.cachep2p.com/api.html) page.

### License

MIT. Copyright (c) [CacheP2P](https://www.CacheP2P.com)
