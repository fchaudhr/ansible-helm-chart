# ansible-helm-chart

Usage: 
`helm repo add <local-name> https://fchaudhr.github.io/ansible-helm-chart/`

Example:
`helm repo add ansible-repo https://fchaudhr.github.io/ansible-helm-chart/`

Verify helm repo name:
`helm repo list`

Search helm repo:
`helm search repo ansible`

Install:
`helm install <local-name> <repo-name>'

`helm install ansible ansible-repo/ansible`
