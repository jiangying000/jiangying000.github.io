# jiangying000.github.io

## 301, 302, 307
301 permanent redirect

302 temperary redirect，but may change method to 'GET'， 可能把改变请求的方法为 GET

307 internal redirect, 会保留原来的方法，原请求是 POST，浏览器仍然以 POST 请求 response header 里的 Location

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
