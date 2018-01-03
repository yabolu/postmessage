1. 以mac为例, vi /etc/posts, 添加

```
127.0.0.1 a.jrg.com
127.0.0.1 b.jrg.com
```
2. `cd postmessage`

3. `http-server -c-1`

4. 访问: http://a.jrg.com:8080/a.html