
```shell
# wsl terminal
# terminal1 抓包
tcpdump -nn host $(dig +short example.com) -w web.pcap
# terminal2 发送请求
curl http://example.com

mv web.pcap /mnt/c/Users/yeshan/Desktop/web.pcap
# wireshark 看包 Statistics -> Flow Graph
```

wireshark 使用（如果看了这个你还是不会用Wireshark，那就来找我吧）：https://www.dell.com/community/%E5%85%A5%E9%97%A8%E7%BA%A7%E5%92%8C%E4%B8%AD%E7%AB%AF/%E5%A6%82%E6%9E%9C%E7%9C%8B%E4%BA%86%E8%BF%99%E4%B8%AA%E4%BD%A0%E8%BF%98%E6%98%AF%E4%B8%8D%E4%BC%9A%E7%94%A8Wireshark-%E9%82%A3%E5%B0%B1%E6%9D%A5%E6%89%BE%E6%88%91%E5%90%A7-8%E6%9C%886%E6%97%A5%E5%AE%8C%E7%BB%93/td-p/7007033