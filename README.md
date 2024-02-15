* Cheatsheet
```bash
terraform init
terraform apply
```
<img src="https://github.com/tonus-sebastian/eks-aws/assets/52061104/2f0ee42b-4efa-4314-acfa-5423d4490da9" width=50% height=50%>
<img src="https://github.com/tonus-sebastian/eks-aws/assets/52061104/678bf4a7-8deb-47e3-9383-4cd5b2aebef1" width=50% height=50%>
<img src="https://github.com/tonus-sebastian/eks-aws/assets/52061104/d1d91d90-81ce-4329-ba0a-5ad7d49b6de5" width=50% height=50%>
<img src="https://github.com/tonus-sebastian/eks-aws/assets/52061104/13a19bad-1eab-42bd-8ea1-74df7f0320c6" width=50% height=50%>

```bash
aws eks --region us-east-2 describe-cluster --name demo=eks --query cluster.status
aws eks --region us-east-2 update-kubeconfig --name demo-eks
```


```bash
terraform destroy
```


reference  : <a href="https://antonputra.com/terraform/how-to-create-eks-cluster-using-terraform/#create-eks-cluster-using-terraform"> Deploy EKS </a>