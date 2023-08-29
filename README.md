# ansible-helm-chart 

Install kubernetes service with a single pod that has ansible, gitlab and Openrc (SSH server).  Service exposes (nodeport) SSH access to pod/container

## Usage
Add the repo: 
`helm repo add <local-name> https://fchaudhr.github.io/ansible-helm-chart/`

### Example:
`helm repo add ansible-repo https://fchaudhr.github.io/ansible-helm-chart/`

### Verify helm repo name
`helm repo list`

### Search helm repo
`helm search repo ansible`

### Install
`helm install <local-name> <repo-name>`
E.g.
`helm install ansible ansible-repo/ansible`

### verify helm list

`helm list -n ansible`
