# Module to deploy ArgoCD ROOT Applicaiton to EKS

Example to use:

```
module "argocd_root" {
  source             = "./terraform_argocd_root_eks"
  eks_cluster_name   = "demo-dev"
  git_source_path    = "demo-dev/applications"
  git_source_repoURL = "git@github.com:yurii-chornyi/argocd.git"
}
```
