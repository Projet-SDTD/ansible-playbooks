# ansible-playbooks

This repo contains the ansible playbook used to deploy all our SDTD devops/dev/sre services and deployments on the cluster.
This is highly recommended to use it inside the pipeline in `deploy.py`

## How to use
This is highly recommended to use it inside the pipeline in `deploy.py`
However, if you want te deploy manually, you can use `dansible-playbook -i <inventory> initial-kubernetes.yaml`
