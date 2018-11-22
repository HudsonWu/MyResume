# MyResume 

from: [简历生成器](https://github.com/izuolan/zresume)</br>

## 手动启动

<pre>
docker run -d --name resume \
  -e PASSWORD=5baa61e4c9b93f3f0682250b6cf8331b7ee68fd8 \ # 此为"password"的sha_1混淆
  -p 6666:80 \
  --restart=always \
  -v ~/Resume/themes:/usr/html/user/themes \
  -v ~/Resume/pages:/usr/html/user/pages \
  -v ~/Resume/config:/usr/html/user/config \
  zuolan/resume
</pre>
在线密码生成器 [http://www.sha1-online.com](http://www.sha1-online.com)<br/>



