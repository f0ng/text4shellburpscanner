# text4shellburpscanner

本项目基于[log4j2burpscanner](https://github.com/f0ng/log4j2burpscanner) 修改而来，删除了主动扫描功能，后续有需要再加上

CVE2022-42889

靶场链接如下：

https://github.com/karthikuj/cve-2022-42889-text4shell-docker.git

也可以关注主页公众号（only security），回复`text4shell`获取编译好的靶场下载地址

靶场搭建:

cd 进目录，执行

```bash
docker run -p 85:8080 text4shell
```

![image-20221209164009559](/Users/f0ng/Library/Application Support/typora-user-images/image-20221209164009559.png)

访问`http://ip地址/text4shell/attack?search=111`即可

![image-20221209164107617](/Users/f0ng/Library/Application Support/typora-user-images/image-20221209164107617.png)

在插件页面即可看到漏洞存在

![image-20221209165349525](/Users/f0ng/Library/Application Support/typora-user-images/image-20221209165349525.png)

![image-20221209165738556](/Users/f0ng/Library/Application Support/typora-user-images/image-20221209165738556.png)



