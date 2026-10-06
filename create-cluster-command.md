##### EKSCTL create cluster command

```
eksctl create cluster \
—name demo-cluster \
—version 1.36 \
—region eu-north-1 \
—nodegroup-name demo-nodes \
—node-type t3.small \
—nodes 2 \
—nodes-min 1 \
—nodes-max 3
```
#### Create cluster with yaml file
##### AWS Cluster Doc: https://docs.aws.amazon.com/eks/latest/eksctl/creating-and-managing-clusters.html 
```
AWS_PROFILE=asambataiden-dev eksctl create cluster -f eks-cluster.yaml

```