k8s-ckad-exam servers

k8s-ckad-exam-control
 - ssh cloud_user@18.170.218.76
 - 18.170.218.76
 - 172.31.120.114
 - 135ff962b22c.mylabserver.com
 - 135ff962b22d.mylabserver.com

k8s-ckad-exam-worker-1
 - ssh cloud_user@18.135.100.212
 - 13.40.73.137
 - 172.31.120.171    
 - Public Hostnames
 - 135ff962b21c.mylabserver.com
 - 135ff962b21d.mylabserver.com
     
k8s-ckad-exam-worker-2
 - ssh cloud_user@13.40.73.137
 - 13.40.73.137
 - 172.31.120.171
 - Public Hostnames
 - 135ff962b23c.mylabserver.com
 - 135ff962b23d.mylabserver.com

sudo vi /etc/hosts
```
172.31.120.114 k8s-control
172.31.120.171 k8s-worker1
172.31.120.171 k8s-worker2
```
