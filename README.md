# amazon EKS day 2018 time:Aug,30,2018

Step
```
step 1: 啟動hybrid our amazon eks cluster with OD/RI + SpotFleets

step 2: Traefik Ingress and ALB
```

Resources:
```
github:https://github.com/pahud/amazon-eks-workshop
```

Getting Started
```
Create your EKS Cluster with eksctl：

Installing Helm：套件，類似npm install ，yarm install 的感覺

Customize your nodegroup(worker nodes)：客製化方法

Working with kubectl for basic administrations：指令說明
```



SpotFleet Configuration instance 建議到t2 即可

port-forward 可以變成類似本機端

LoadBalancer ：把端口網上掛CLB

demo sample golang版
https://github.com/pahud/greeting
