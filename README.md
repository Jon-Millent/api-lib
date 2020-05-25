# api-lib
Free api collection

## Get ip address

* **https://www.cloudflare.com/cdn-cgi/trace**
  * `method: GET`
  * `cross-domain: yes`
  * `content-type: text/plain `
  * `https: yes`
  * `response time: 100ms - 230ms`
  * `response`
    ```text
    fl=12f247
    h=www.cloudflare.com
    ip=x.x.x.x
    ts=1590396977.894
    visit_scheme=https
    uag=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/80.0.3987.149 Safari/537.36
    colo=LAX
    http=http/2
    loc=CN
    tls=TLSv1.3
    sni=plaintext
    warp=off
    ```
  * `request: /`
  
* **http://pv.sohu.com/cityjson**
  * `method: GET`
  * `cross-domain: no`
  * `content-type: text/json `
  * `https: yes`
  * `response time: 25ms - 100ms`
  * `response`
    ```text
    var returnCitySN = {"cip": "x.x.x.x", "cid": "xxxx", "cname": "xx省xx市"};
    ```
  * `request: /  `
