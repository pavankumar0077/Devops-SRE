
![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/1311b380-7b1e-4343-a87b-68c659b855e8)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/2a3ffb56-bc35-47e6-ba22-311715fe5305)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/e1ccebf9-cec1-4ef4-b7e8-21c19be8057c)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/85379592-e745-41e0-91e4-113df046da05)

Master node
--
1) API SERVER
2) ETCD -- It is like DB (data present in kubectl deploy.yaml -- will take)
3) Control manager -- Brain of kubernetes (Controls master and worker nodes ) (Multipl managers -- RS, Network, S)
4) Scheduler -- schedule the deployments or services 

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/3fd4048b-3d24-4f1c-95fd-fbd9f41b0b9f)

3) Control manager will tell sheduling of the task to nodes

Worker node
--
1) Kubelet -- Sends or recieves from the parent/master always listens to master and sends the data and receives the data from master
2) Pod - containers
3) Container runtime -- containerd (metrics) 
4) Kube-proxy --  network/routering configs 

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/a63dbafb-2414-4206-9586-5a456b65c4e3)

``` ENV USE_HTTP 0``` -- Backend proxy server setup for docker file

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/58442d7e-4590-4e83-89d3-403edcd3a8dc)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/c8571ff5-e196-450d-be3c-4800801b58ef)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/cb77828a-2f24-4131-939e-9e2834d1f4a7)

```nginx``` ```webserver ```

1) api version -- api server will have apps/v1 stored in it (end point) api version is the calling function of kubernetes. Version can be chanegd
2) kind -- deployment, ingress, service, stateful 
3) metadata -- info about info (Additonal data to identify the pod or deployment), 
4) spec -- which conatiner and name label and port image
5) pod -- can have any no of conatiners

1) Cluster Ip -- talk to other nodes in same cluster
1) Nodeport ---        30000 to 32000 --- static port --

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/0811a9b4-baf5-467d-99c7-cf9db9391944)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/1c76ae76-60ec-457c-9d08-11ea159aac42)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/ebfc7f14-91b9-4b66-89da-f2dd2cbee762)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/5e31f397-3d13-465b-bf6b-3d78431b7397)

![image](https://github.com/pavankumar0077/Devops-SRE/assets/40380941/cc282c3d-9b6f-4392-a832-fc530d4171c6)

OIDC connect -- like IAM for EKS

1) ``` Conntract ``` -- type of minikube

2) ``` kubectl get ns ``` for namespaces
3) ```kubectl create -f demo-app.yaml -n pavan ``` To create on specific namespace -- pavan is namespace

