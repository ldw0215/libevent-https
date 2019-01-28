# libevent-https
  用libevent实现https服务器  
  
依赖
---
  libevent 2.1以上版本  
  
使用
---
  make
  
测试
---
    命令：curl -H "Content-Type:application/json" -H "sign:10A8630BEA9CEEC895B6C745C24B3605" -H "appCode:0" -H "timestamp:1547723688" -X POST --connect-timeout 2 -m 2 -k -g -d '{"time":1547723688,"sessionID":"BC4063A88B3C46EA","sid":"60AE1B026F0BFDB5"}' https://127.0.0.1:8080/rest/atas/sessionBegin.do  
    
    
    
