# jiangying000.github.io

## 301, 302, 307

301 permanent redirect，永久重定向，浏览器缓存时间长，第一次之后浏览器内部直接重定向，少用一个http请求，搜索引擎可能此后不再抓取原地址

302 temperary redirect，临时重定向，可能把改变请求的方法为 GET，比如 CAS gateway 登录时会用到，https://cas.com/login?service=https://my-service.com&gateway=true

307 internal redirect, 临时重定向，会保留原来的方法，原请求是 POST，浏览器仍然以 POST 请求 response header 里的 Location

地址栏输入 jiangying000.github.io， 就会使用  307 
```
Request URL: http://jiangying000.github.io/
Request Method: GET
Status Code: 307 Internal Redirect
Referrer Policy: strict-origin-when-cross-origin
Cross-Origin-Resource-Policy: Cross-Origin
Location: https://jiangying000.github.io/
Non-Authoritative-Reason: HSTS
```
![image](https://user-images.githubusercontent.com/23182033/202351439-b49d0be9-c34d-49c9-b600-f82b234e16a0.png)

https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/301

https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/302

https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/307
