
# Change Log
All notable changes to this project will be documented in this file.

## [1.1.0] - 2020-11-05

### Upgrade Notes: 
- This upgrade switches the ingress infrastructure from alb-ingress-controller to [alb-loadbalancer-controler](https://github.com/kubernetes-sigs/aws-load-balancer-controller). 

To Upgrade, simply run the eks-deploy-cluster.playbook.yaml with your parameters. Be sure to test and evaluate beforehand! 
 
### Changed
- Switched the ingress controller deployment to utilize the freshly released [alb-loadbalancer-controler](https://github.com/kubernetes-sigs/aws-load-balancer-controller)

### Fixes
- typo at the master playbook (tasks instead of task) did prevent deployment. This is fixed

## [1.0.0] - inital release

### inital version