# Nginx Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of resources covering Nginx, Nginx + Lua, OpenResty and Tengine.

This list is maintained by [Frederic Cambus](https://www.cambus.net). For updates, follow me on Twitter: [@fcambus](https://twitter.com/fcambus)

## Understanding Nginx

- [History of Nginx](https://www.nginx.com/wp-content/uploads/2014/11/Infographic_History-of-Nginx_FulI_20141101.png)
- [Understanding Nginx versioning](https://www.nginx.com/blog/nginx-1-6-1-7-released/)
- [Interview with the creator of Nginx](http://mindend.com/index.php/interview-with-the-creator-of-nginx/)
- [Interview with Igor Sysoev, author of Apache's competitor NGINX](http://freesoftwaremagazine.com/articles/interview_igor_sysoev_author_apaches_competitor_nginx/)
- [The case for Nginx in front of application servers](https://www.cambus.net/the-case-for-nginx-in-front-of-application-servers/)
- [Nginx Optimization: understanding sendfile, tcp_nodelay and tcp_nopush](https://t37.net/nginx-optimization-understanding-sendfile-tcp_nodelay-and-tcp_nopush.html)

## Architecture

- [The Architecture of Open Source Applications (Volume 2): nginx](http://aosabook.org/en/nginx.html)
- [Nginx Guts - Shedding light on Nginx internals](http://www.nginxguts.com/category/nginx/)
- [Nginx discovery journey](http://www.nginx-discovery.com/)
- [Nginx Internals](http://www.slideshare.net/joshzhu/nginx-internals)
- [Inside NGINX: How We Designed for Performance & Scale](https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/)
- [Thread Pools in NGINX](https://www.nginx.com/blog/thread-pools-boost-performance-9x/)

## Configuration

- [Beginner's Guide](http://nginx.org/en/docs/beginners_guide.html)
- [Alphabetical index of variables](http://nginx.org/en/docs/varindex.html)
- [Nginx Pitfalls](https://www.nginx.com/resources/wiki/start/topics/tutorials/config_pitfalls/)
- [Useful Rewrites for Nginx ](https://blog.engineyard.com/2011/useful-rewrites-for-nginx)
- [Nginx Configuration Primer](http://blog.martinfjordvald.com/2010/07/nginx-primer/)
- [Nginx Primer 2: From Apache to Nginx](http://blog.martinfjordvald.com/2011/02/nginx-primer-2-from-apache-to-nginx/)
- [Understanding the Nginx Configuration Inheritance Model](http://blog.martinfjordvald.com/2012/08/understanding-the-nginx-configuration-inheritance-model/)
- [Nginx HTTP server boilerplate configs](https://github.com/h5bp/server-configs-nginx)
- [Nginx Boilerplate - Configuration template and a set of handy must-have snippets](https://github.com/nginx-boilerplate/nginx-boilerplate)
- [Cranking Nginx to 11](https://speakerdeck.com/helgi/cranking-nginx-to-11)
- [Nginx and PHP, match made in heaven](https://speakerdeck.com/helgi/nginx-and-php-match-made-in-heaven)
- [How to Configure OCSP Stapling in Apache and Nginx](https://sslmate.com/blog/post/ocsp_stapling_in_apache_and_nginx)

## Tutorials

- [NGINX and NGINX Plus Admin Guide](https://www.nginx.com/resources/admin-guide/)
- [agentzh's Nginx Tutorials](https://openresty.org/download/agentzh-nginx-tutorials-en.html) ([Source](https://github.com/openresty/nginx-tutorials))
- [Introduction to nginx.conf scripting](http://agentzh.org/misc/slides/nginx-conf-scripting/nginx-conf-scripting.html)
- [Load Balancing with NGINX and NGINX Plus](https://www.nginx.com/blog/load-balancing-with-nginx-plus/) ([Part 2](https://www.nginx.com/blog/load-balancing-with-nginx-plus-part2/))
- [Optimizing Nginx for High Traffic Loads](http://blog.martinfjordvald.com/2011/04/optimizing-nginx-for-high-traffic-loads/)
- [Nginx Load Balancing Basics](http://blog.jsdelivr.com/2013/01/nginx-load-balancing-basics.html)
- [NGINX as a WebSockets Proxy](https://www.nginx.com/blog/websocket-nginx/)
- [HTTP Keepalive Connections and Web Performance ](https://www.nginx.com/blog/http-keepalives-and-web-performance/)
- [CORS on Nginx](https://enable-cors.org/server_nginx.html)
- [Using NGINX As An Intelligent Proxy & Web Server](https://docs.apitools.com/blog/2014/06/10/using-nginx-as-an-intelligent-proxy-web-server.html)
- [Serving precompressed content with Nginx and Zopfli](https://www.cambus.net/serving-precompressed-content-with-nginx-and-zopfli/)
- [Nginx on FreeBSD](https://www.cambus.net/nginx-on-freebsd/)
- [Using New Debugging Features to Probe NGINX Internals](https://www.nginx.com/blog/new-debugging-features-probe-nginx-internals/)
- [Performing A/B Testing with NGINX and NGINX Plus](https://www.nginx.com/blog/performing-a-b-testing-nginx-plus/)

## Modules development

- [Official Development Guide](http://nginx.org/en/docs/dev/development_guide.html)
- [Guide to Nginx Module Development](http://www.evanmiller.org/nginx-modules-guide.html)
- [Advanced Topics In Nginx Module Development](http://www.evanmiller.org/nginx-modules-guide-advanced.html)
- [Developing Nginx Modules](https://www.airpair.com/nginx/extending-nginx-tutorial)

## APIs

- [Telize - JSON IP and GeoIP REST API (IP Geolocation) built on Nginx and Lua](https://www.telize.com)
- [GIN - JSON-API framework](http://gin.io/)
- [Outbound API rate limits: the nginx way](https://monterail.com/blog/2011/outbound-api-rate-limits-the-nginx-way)
- [Using Nginx to comply with a third-party API's rate limits](https://vitobotta.com/2014/01/12/using-nginx-to-comply-with-a-third-party-apis-rate-limits/)
- [Simple API with Nginx and PostgreSQL](http://rny.io/nginx/postgresql/2013/07/26/simple-api-with-nginx-and-postgresql.html)
- [Kong - Management Layer for Microservices and APIs](https://getkong.org)

## Hacks

- [Nginx JSON hacks](https://web.archive.org/web/20140921162448/http://www.gabrielweinberg.com/blog/2011/07/nginx-json-hacks.html)
- [Using Environment Variables In Nginx.conf](https://docs.apitools.com/blog/2014/07/02/using-environment-variables-in-nginx-conf.html)
- [JSONP Proxy - Get JSONP from APIs not supporting it natively](https://github.com/fcambus/jsonp-proxy)
- [Log rotation directly within Nginx configuration file](https://www.cambus.net/log-rotation-directly-within-nginx-configuration-file/)
- [Realtime pixel tracking with Nginx, syslog-ng, and Redis](https://benwilber.github.io/nginx/redis/syslog/pixel-tracking/2013/09/13/realtime-pixel-tracking-with-nginx-syslog-ng-and-redis.html)
- [Dynamic log formats in Nginx](https://benwilber.github.io/nginx/syslog/logging/2015/08/26/dynamic-log-formats-in-nginx.html)
- [Capture and delay unwanted requests](https://github.com/p0pr0ck5/lua-resty-tarpit)
- [Nginx: a caching, thumbnailing, reverse proxying image server?](http://charlesleifer.com/blog/nginx-a-caching-thumbnailing-reverse-proxying-image-server-/)

## Tips

- [Things you didn't know Nginx could do](http://www.slideshare.net/sarahnovotny/5-things-you-didnt-know-nginx-could-do)
- [Finding the nginx gzip_comp_level sweet spot](https://mjanja.ch/2015/03/finding-the-nginx-gzip_comp_level-sweet-spot/)

## Nginx + Lua

- [Nginx, Lua, and beyond](http://agentzh.org/misc/slides/nginx-lua-and-beyond.pdf)
- [Pushing Nginx to its limit with Lua](https://blog.cloudflare.com/pushing-nginx-to-its-limit-with-lua/)
- [Scripting Nginx with Lua](http://www.londonlua.org/scripting_nginx_with_lua/)
- [Augmenting APIs with Nginx and Lua](http://tech.3scale.net/2013/01/09/augment-your-api-without-touching-it/)
- [Adding OAuth Support to Nginx via Lua](http://chairnerd.seatgeek.com/oauth-support-for-nginx-with-lua/)
- [Scripting libdrizzle with Lua inside Nginx](http://agentzh.org/misc/slides/libdrizzle-lua-nginx.pdf)
- [Nginx and Lua](https://web.archive.org/web/20141223070856/http://devblog.mixlr.com/2012/09/01/nginx-lua/)
- [Writing an Nginx authentication module in Lua](https://www.stavros.io/posts/writing-an-nginx-authentication-module-in-lua/)
- [Scaling TextRazor in the Cloud with Nginx and Lua](http://www.textrazor.com/blog/2013/03/scaling-textrazor-in-the-cloud-with-nginx-and-lua.html)
- [LSSO - Lua + Nginx SSO System with an OAuth Backend](https://github.com/maiome-development/lsso)
- [Measuring Nginx Cache Performance using Lua and Redis](http://charlesleifer.com/blog/measuring-nginx-cache-performance-using-lua-and-redis/)

## OpenResty

- [OpenResty - Fast web app server by extending Nginx](https://openresty.org/en/)
- [Lapis - A web framework for Lua or MoonScript powered by OpenResty](http://leafo.net/lapis/)
- [Nginx image processing server with OpenResty and Lua](http://leafo.net/posts/creating_an_image_server.html)
- [A small router for Openresty](https://docs.apitools.com/blog/2014/04/24/a-small-router-for-openresty.html)
- [Building an OpenResty events server](https://github.com/cagerton/dropthat/)
- [SysAdvent 2014 - OpenResty, Nginx and Lua](http://sysadvent.blogspot.com/2014/12/day-22-largely-unappreciated.html) ([Source](https://github.com/lusis/sysadvent-2014))
- [OpenResty (Nginx) with dynamically generated certificates](http://blog.dutchcoders.io/openresty-with-dynamic-generated-certificates/)
- [Ceryx - A dynamic reverse proxy](https://www.sourcelair.com/blog/articles/75/ceryx-dynamic-nginx)
- [An Introduction To OpenResty](http://openmymind.net/An-Introduction-To-OpenResty-Nginx-Lua/)
- [Developing OpenResty Framework using decoupled libraries](http://www.iresty.com/download/ebook/2015_con/aapo.pdf) ([Video](https://www.youtube.com/watch?v=VqBt5icKCI8))
- [Programming OpenResty (written by the OpenResty creator)](https://www.gitbook.com/book/openresty/programming-openresty/details)
- [VeryNginx - Nginx distribution which provides WAF, Control Panel, and Dashboards](https://github.com/alexazhou/VeryNginx)

- [OpenResty Con 2015](http://www.iresty.com)


## Tengine

- [Tengine Web Server](http://tengine.taobao.org)
- [Difference between OpenResty and Tengine](https://github.com/openresty/openresty/issues/54)

## Talks

- [NGINX Conference 2016 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXcOsB_dT26iu0BvbSxWYG1g)
- [NGINX Conference 2015 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXdED9BR6GQ61A6d3fBzjpbn)
- [NGINX Conference 2014 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXewvc6tjIGGFZ6DBKHEld3k)
- [NGINX Conference](https://www.nginx.com/nginxconf/)
- [NGINX User Summit 2014 - Lightning talks](https://www.youtube.com/playlist?list=PLGz_X9w9raXfTnRnI6Xl0LMhAKoTVVZv8)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Frederic Cambus](https://www.cambus.net) has waived all copyright and related or neighboring rights to this work.
