1Unbreak.list 
需直连防广告拦截的域名,iOS应用企业证书吊销依旧可用,參考
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Unbreak.list

2Ad.list 
广告拦截,直接reject,删除对crashlytics.com的拦截,修改自 
https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/AdBlock.list

3Speedtest.list

4NoGFW.list 
可直连不需代理的域名,提取自 
http://s5s5.github.io/GFWListToSurgeRule.js/

5Mail.list 
Gmail和Outlook邮箱走代理,复制 
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Mail.list

6Telegram.list 
Telegram走代理,合并自
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/Telegram.list
https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/规则片段集/App%20规则集/社交分享/Telegram.txt

7GFWmedia.list 
境外视频音乐走代理,复制 
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/GlobalMedia.list

8GFW.list 
GFW全域名列表,提取自 
http://s5s5.github.io/GFWListToSurgeRule.js/

9CN.list 
国内域名直连,删除 DOMAIN-SUFFIX,cn,DIRECT 以及 GEOIP,CN,DIRECT ,提取Apple和Speedtest规则,提取自 
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/China.list

10Apple.list
从9CN中单列出来

11IP.list 国内/香港IP直连

Rewrite.conf
复制
https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Rewrite.conf