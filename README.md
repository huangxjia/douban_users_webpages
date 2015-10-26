# douban_users_webpages

This is a practice for crawl study, the only improvement I did is as below:

s=requests.Session()
s.proxies={"http": "http://61.233.25.166:80"}
#proxyInfo='127.0.0.1:8087'
#proxySupport=urllib2.ProxyHandler({'http':proxyInfo})
#opener=urllib2.build_opener(proxySupport)
#urllib2.install_opener(opener)
#This doesn't work, so changed it to request, and it worked

all content is from http://www.cnblogs.com/xiaff/p/4858337.html
