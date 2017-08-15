# Microservice API Gateways with NGINX

Slides from talk given on Tuesday August 2nd, 2017 at the Denver Open Source Users Group (DOSUG).

>(NGINX is pronounced "engine x".) 

>Microservices are a popular architectural solution. Clients of microservices may experience some difficulty keeping track of the various instances and endpoints they have to call. An API gateway can help manage large numbers of microservices and hide the infrastructure complexity from your clients. We will review a microservice architecture before and after the addition of an API gateway. 

>An API gateway is a reverse proxy. A reverse proxy handles incoming requests from clients and calls a service to get the data to satisfy that request. The reverse proxy returns that data to the client. Many developers write these proxies by hand in custom code, not realizing there better solutions available. We will mention a number of popular solutions, some open source and some cloud-based services. For this talk, we will focus on NGINX, a popular open source reverse proxy and API Gateway. (NGINX also sells an enterprise offering, NGINX Plus, but this talk will only cover the features available in the open-source version.) 

>We will show how to set up NGINX as an API Gateway. We will dive into the configuration and operation of NGINX. 

[Markdown](api-gateway-nginx.md)

[PDF](Microservice%20API%20Gateways%20with%20NGINX.pdf)

This slideshow was written using [reveal.js](https://github.com/hakimel/reveal.js)

The interactive diagrams were implemented with [d3](https://d3js.org) and [Hierarchical Edge Bundling](https://bl.ocks.org/mbostock/7607999)

