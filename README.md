# Tinyme

## This is a URL Shortner made using [Cloudflare Workers](https://workers.cloudflare.com/). Made as part of the [Spring Developer Challenge](https://blog.cloudflare.com/announcing-our-spring-developer-challenge/). 

 - The URL Shortner serves a simple HTML Page for Index Page
 - Used [Cloudflare KV](https://www.cloudflare.com/products/workers-kv/) as a simple Key-Value Pair to store the shortned url tag and the Original URL.
 - When any get request is performed, say for ```/short_url``` the worker looks for a key: ```short_url``` in the KV and if it exists returns a Redirection response to the corresponding orginal URL. 
