# Nginx Resources

A collection of resources covering Nginx, Nginx + Lua, OpenResty and Tengine. 

This list is maintained by [Frederic Cambus](http://www.cambus.net). For updates, follow me on Twitter : [@fcambus](https://twitter.com/fcambus)

## Understanding Nginx

- [History of Nginx](http://nginx.com/wp-content/uploads/2014/11/Infographic_History-of-Nginx_FulI_20141101.png)
- [Understanding Nginx versioning](http://nginx.com/blog/nginx-1-6-1-7-released/)
- [Interview with creator of NGINX Igor Sysoev](http://www.webhostingskills.com/open_source/articles/interview_with_creator_of_nginx_igor_sysoev/) ([Better traduction](https://mindend.com/index.php/interview-with-the-creator-of-nginx/))
- [Interview with Igor Sysoev, author of Apache's competitor NGINX](http://www.freesoftwaremagazine.com/articles/interview_igor_sysoev_author_apaches_competitor_nginx)
- [The case for Nginx in front of application servers](http://www.cambus.net/the-case-for-nginx-in-front-of-application-servers/)

## Architecture

- [The Architecture of Open Source Applications (Volume 2): nginx](http://aosabook.org/en/nginx.html)
- [Nginx Guts - Shedding light on Nginx internals](http://www.nginxguts.com/category/nginx/)
- [Nginx discovery journey](http://www.nginx-discovery.com/)
- [Nginx Internals](http://www.slideshare.net/joshzhu/nginx-internals)

## Configuration 

- [Beginner's Guide](http://nginx.org/en/docs/beginners_guide.html)
- [Alphabetical index of variables](http://nginx.org/en/docs/varindex.html)
- [Nginx Pitfalls](http://wiki.nginx.org/Pitfalls)
- [Nginx Secure Web Server with HTTP, HTTPS SSL and Reverse Proxy Examples](https://calomel.org/nginx.html)
- [Useful Rewrites for Nginx ](https://blog.engineyard.com/2011/useful-rewrites-for-nginx/)
- [Nginx Configuration Primer](http://blog.martinfjordvald.com/2010/07/nginx-primer/)
- [Nginx Primer 2: From Apache to Nginx](http://blog.martinfjordvald.com/2011/02/nginx-primer-2-from-apache-to-nginx/)
- [Understanding the Nginx Configuration Inheritance Model](http://blog.martinfjordvald.com/2012/08/understanding-the-nginx-configuration-inheritance-model/)
- [Nginx HTTP server boilerplate configs](https://github.com/h5bp/server-configs-nginx)
- [Nginx Boilerplate - Configuration template and a set of handy must-have snippets](https://github.com/Umkus/nginx-boilerplate)
- [Cranking Nginx to 11](https://speakerdeck.com/helgi/cranking-nginx-to-11)
- [Nginx and PHP, match made in heaven](https://speakerdeck.com/helgi/nginx-and-php-match-made-in-heaven)

## Tutorials

- [NGINX and NGINX Plus Admin Guide](http://nginx.com/resources/admin-guide/)
- [agentzh's Nginx Tutorials](http://openresty.org/download/agentzh-nginx-tutorials-en.html) ([Source](https://github.com/openresty/nginx-tutorials))
- [Introduction to nginx.conf scripting](http://agentzh.org/misc/slides/nginx-conf-scripting/nginx-conf-scripting.html)
- [Load Balancing with NGINX and NGINX Plus](http://nginx.com/blog/load-balancing-with-nginx-plus/) ([Part 2](http://nginx.com/blog/load-balancing-with-nginx-plus-part2/))
- [Optimizing Nginx for High Traffic Loads](http://blog.martinfjordvald.com/2011/04/optimizing-nginx-for-high-traffic-loads/)
- [Nginx Load Balancing Basics](http://blog.jsdelivr.com/2013/01/nginx-load-balancing-basics.html)
- [NGINX as a WebSockets Proxy](http://nginx.com/blog/websocket-nginx/)
- [HTTP Keepalive Connections and Web Performance ](http://nginx.com/blog/http-keepalives-and-web-performance/)
- [CORS on Nginx](http://enable-cors.org/server_nginx.html)
- [Using NGINX As An Intelligent Proxy & Web Server](https://docs.apitools.com/blog/2014/06/10/using-nginx-as-an-intelligent-proxy-web-server.html)
- [Serving precompressed content with Nginx and Zopfli](http://www.cambus.net/serving-precompressed-content-with-nginx-and-zopfli/)
- [Nginx on FreeBSD](http://www.cambus.net/nginx-on-freebsd/)

## Modules development

- [Guide to Nginx Module Development](http://www.evanmiller.org/nginx-modules-guide.html)
- [Advanced Topics In Nginx Module Development](http://www.evanmiller.org/nginx-modules-guide-advanced.html)
- [Developing Nginx Modules](http://www.airpair.com/nginx/extending-nginx-tutorial)

## APIs

- [Telize is a JSON IP and GeoIP REST API (IP Geolocation) built on Nginx and Lua](http://www.telize.com)
- [GIN JSON-API framework](http://gin.io/)
- [Outbound API rate limits: the nginx way](http://codetunes.com/2011/07/26/outbound-api-rate-limits-the-nginx-way)
- [Using Nginx to comply with a third-party API's rate limits](http://vitobotta.com/nginx-proxy-comply-api-rate-limits/)
- [Simple API with Nginx and PostgreSQL](http://rny.io/nginx/postgresql/2013/07/26/simple-api-with-nginx-and-postgresql.html)

## Hacks

- [Nginx JSON hacks](http://www.gabrielweinberg.com/blog/2011/07/nginx-json-hacks.html)
- [Using Environment Variables In Nginx.conf](https://docs.apitools.com/blog/2014/07/02/using-environment-variables-in-nginx-conf.html)
- [JSONP Proxy - Get JSONP from APIs not supporting it natively](https://github.com/fcambus/jsonp-proxy)
- [Log rotation directly within Nginx configuration file](http://www.cambus.net/log-rotation-directly-within-nginx-configuration-file/)

## Tips

- [A/B testing using ngx_http_split_clients_module](https://twitter.com/maximkonovalov/statuses/354907254216065024)
- [Logging $tcpinfo_rtt to measure typical RTT](https://twitter.com/maximkonovalov/statuses/352436564934148096)

## Nginx + Lua

- [Nginx, Lua, and beyond](http://agentzh.org/misc/slides/nginx-lua-and-beyond.pdf)
- [Pushing Nginx to its limit with Lua](http://blog.cloudflare.com/pushing-nginx-to-its-limit-with-lua/)
- [Scripting Nginx with Lua](http://www.londonlua.org/scripting_nginx_with_lua/)
- [Augmenting APIs with Nginx and Lua](http://tech.3scale.net/2013/01/09/augment-your-api-without-touching-it/)
- [Adding OAuth Support to Nginx via Lua](http://chairnerd.seatgeek.com/oauth-support-for-nginx-with-lua/)
- [Scripting libdrizzle with Lua inside Nginx](http://agentzh.org/misc/slides/libdrizzle-lua-nginx.pdf)
- [Nginx and Lua](http://devblog.mixlr.com/2012/09/01/nginx-lua/)
- [Writing an Nginx authentication module in Lua](http://www.stavros.io/posts/writing-an-nginx-authentication-module-in-lua/)
- [Scaling TextRazor in the Cloud with Nginx and Lua](http://www.textrazor.com/blog/2013/03/scaling-textrazor-in-the-cloud-with-nginx-and-lua.html)

## OpenResty

- [OpenResty  a fast web app server by extending nginx ](http://openresty.org/)
- [Lapis - A web framework for Lua or MoonScript powered by OpenResty](http://leafo.net/lapis/)
- [Nginx image processing server with OpenResty and Lua](http://leafo.net/posts/creating_an_image_server.html)
- [A small router for Openresty](https://docs.apitools.com/blog/2014/04/24/a-small-router-for-openresty.html)
- [Building an OpenResty events server](https://github.com/cagerton/dropthat/)

## Tengine

- [Tengine Web Server ](http://tengine.taobao.org)
- [Difference between OpenResty and Tengine](https://github.com/openresty/ngx_openresty/issues/54)

## Talks

- [NGINX Conference 2014](http://nginx.com/nginxconf/)
- [NGINX Conference 2014 Videos](https://www.youtube.com/playlist?list=PLGz_X9w9raXewvc6tjIGGFZ6DBKHEld3k)
- [NGINX User Summit 2014 - Lightning talks](https://www.youtube.com/playlist?list=PLGz_X9w9raXfTnRnI6Xl0LMhAKoTVVZv8)
