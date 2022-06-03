## Deploying kubernetes cluster with Ansible in the following order
- install-prereq-packages.yaml
- tune-os-settings.yaml
- prepare-kuber-for-install.yaml
- run-the-kuber.yaml
- join_worker.yaml
## Issue
However, I come access an issue with pulling an image from the private docker registry. In particular, the cluster shouts with an error "unknown certificate authority". 
It seems to relate to containerd behaviour https://devops.stackexchange.com/questions/14053/how-to-resolve-a-problem-certificate-signed-by-unknown-authority-in-gke-on-pul/14167#14167
