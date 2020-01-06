###运行topo.py生成拓扑

输入命令```sudo mn --custom topo.py --topo mytopo --controller=remote,ip=127.0.0.1,port=6653 --switch ovsk,protocols=OpenFlow13```

###拓扑创建后运行fzjh.py实现负载均衡

输入命令```sudo python fzjh.py```
