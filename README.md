# Nginx Resources

A growing collection of resources covering Nginx, Nginx + Lua, OpenResty and Tengine. 

This list is maintained by [Frederic Cambus](http://www.cambus.net). For updates and/or suggestions, follow me on Twitter : [@fcambus](https://twitter.com/fcambus)

## Nginx Configuration 

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

## Nginx architecture

- [The Architecture of Open Source Applications (Volume 2): nginx](http://aosabook.org/en/nginx.html)
- [Nginx Guts - Shedding light on Nginx internals](http://www.nginxguts.com/category/nginx/)
- [Nginx discovery journey](http://www.nginx-discovery.com/)
- [Nginx Internals](http://www.slideshare.net/joshzhu/nginx-internals)

## Modules development

- [Guide to Nginx Module Development](http://www.evanmiller.org/nginx-modules-guide.html)
- [Advanced Topics In Nginx Module Development](http://www.evanmiller.org/nginx-modules-guide-advanced.html)
- [Developing Nginx Modules](http://www.airpair.com/nginx/extending-nginx-tutorial)

## SSL / TLS

- [Optimizing NGINX TLS Time To First Byte (TTTFB)](https://www.igvita.com/2013/12/16/optimizing-nginx-tls-time-to-first-byte/)
- [SSL session caching in Nginx](http://www.hezmatt.org/~mpalmer/blog/2011/06/28/ssl-session-caching-in-nginx.html)
- [SSL/TLS & Perfect Forward Secrecy](http://vincent.bernat.im/en/blog/2011-ssl-perfect-forward-secrecy.html)
- [Configuring Apache, Nginx, and OpenSSL for Forward Secrecy](http://blog.ivanristic.com/2013/08/configuring-apache-nginx-and-openssl-for-forward-secrecy.html)
- [Getting an A+ on Qualy's SSL Labs Tester](https://sethvargo.com/getting-an-a-plus-on-qualys-ssl-labs-tester/)

## Nginx Conference 2014

- [NGINX Conference 2014](http://nginx.com/nginxconf/)
- [Making HTTPS Fast(er): Ilya Grigorik @ nginx.conf 2014](https://www.youtube.com/watch?v=iHxD-G0YjiU)
- [The Latest and Greatest from ngx_lua: New Features & Tools: Yichun Zhang](https://www.youtube.com/watch?v=Z0fQabvVhIk)
- [Scaleable NGINX Configuration: Igor Sysoev](https://www.youtube.com/watch?v=YWRYbLKsS0I)
- [Making Sense of SDN and NFV for NGINX: Christian Buerger](https://www.youtube.com/watch?v=-vQpalH8VlE)
- [NGINX Plus Serving Breaking News for InkaBinka: Chris Brahmer ](https://www.youtube.com/watch?v=wxUUEvRLpH8)
- [The LAMP Just Died, Follow the Light: NGINX and PHP-FPM: Bernard Rosset](https://www.youtube.com/watch?v=WR1aZcA1UXs)
- [Building a low-latency WAF inside NGINX using Lua: John Graham-Cumming](https://www.youtube.com/watch?v=nlt4XKhucS4)

## Nginx interviews

- [Interview with creator of NGINX Igor Sysoev](http://www.webhostingskills.com/open_source/articles/interview_with_creator_of_nginx_igor_sysoev/)
- [Interview with Igor Sysoev, author of Apache's competitor NGINX](http://www.freesoftwaremagazine.com/articles/interview_igor_sysoev_author_apaches_competitor_nginx)

## Nginx and APIs

- [Telize is a JSON IP and GeoIP REST API (IP Geolocation) built on Nginx and Lua](http://www.telize.com)
- [GIN JSON-API framework](http://gin.io/)
- [Outbound API rate limits: the nginx way](http://codetunes.com/2011/07/26/outbound-api-rate-limits-the-nginx-way)
- [Using Nginx to comply with a third-party API's rate limits](http://vitobotta.com/nginx-proxy-comply-api-rate-limits/)
- [Simple API with Nginx and PostgreSQL](http://rny.io/nginx/postgresql/2013/07/26/simple-api-with-nginx-and-postgresql.html)

## Nginx Hacks

- [Nginx JSON hacks](http://www.gabrielweinberg.com/blog/2011/07/nginx-json-hacks.html)
- [Using Environment Variables In Nginx.conf](https://docs.apitools.com/blog/2014/07/02/using-environment-variables-in-nginx-conf.html)
- [JSONP Proxy - Get JSONP from APIs not supporting it natively](https://github.com/fcambus/jsonp-proxy)
- [Log rotation directly within Nginx configuration file](http://www.cambus.net/log-rotation-directly-within-nginx-configuration-file/)

## Nginx tips

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

## Additional Information

This resource collection is maintained by Frederic Cambus

- Site : http://www.cambus.net
- Twitter: http://twitter.com/fcambus