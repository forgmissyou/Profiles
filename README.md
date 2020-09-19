#20200914

Rewrite.list 修改自
https://github.com/DivineEngine/Profiles/tree/master/Quantumult/Rewrite

1AdACL.list
修改自

https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanAD.list

https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/BanProgramAD.list

6CN.list 
修改自

https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/X/Filter/China.list

7IP.list 国内/香港IP直连

GFWLIST一级域名

https://github.com/poctopus/gfwlist-plus

https://github.com/Loukky/gfwlist-by-loukky

GFWLIST参考，思路与s5s5略有差异

http://s5s5.github.io/GFWListToSurgeRule.js/

一.Gfwlist提取@@，再提取不含!得whitelist.

二.Gfwlist提取不含@@，再提取不含!得a

1.a提取纯IP地址，转为IP-CIDR，得gfw1

2.a提取关键字，转为DOMAIN-KEYWORD，得gfw2

3.a提取含||，转为DOMAIN-SUFFIX，得gfw3

4.a提取不含||，得b

5.b提取含|，转为DOMAIN，得gfw4

6.b提取不含|，得c

7.c提取.开头的，转为DOMAIN-SUFFIX，得gfw5

8.c提取非.开头的，转为DOMAIN，得gfw6

9.合并gfw1-6，去重
