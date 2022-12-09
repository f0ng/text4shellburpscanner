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

<img width="489" alt="image" src="https://user-images.githubusercontent.com/48286013/206665093-15f059f0-bfb0-48f7-bf0b-ead70134b2bd.png">

访问`http://ip地址/text4shell/attack?search=111`即可

<img width="489" alt="image" src="https://user-images.githubusercontent.com/48286013/206665258-232e4338-a6c4-43da-8d7c-b6b6a48f17af.png">

在插件页面即可看到漏洞存在

<img width="481" alt="image" src="https://user-images.githubusercontent.com/48286013/206665144-56d07d07-fd9c-4868-81e5-fc353f685a08.png">

<img width="489" alt="image" src="https://user-images.githubusercontent.com/48286013/206665169-bc211b1a-e150-4ccf-b5ba-d5e834bf99d9.png">


