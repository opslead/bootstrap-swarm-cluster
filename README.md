# Bootstrap Swarm Cluster

When physical infrastructure used for project there is no real benefits of using Kubernetes on bare metal.
In that case Docker Swarm is good and simple alternative for application deployment.

That project used for preparing Docker Swarm cluster on servers with GPU for ML and BigData projects, 
where applications deployed as Docker containers

### How to run project

1. Update `inventory` file with servers ip addresses and hostnames
2. Update `config/keys` file with SSH public keys
2. Run `bash deploy-swarm`

# Contributing
We'd love for you to contribute to this project. You can request new features by creating an [issue](https://github.com/opslead/bootstrap-swarm-cluster/issues), or submit a [pull request](https://github.com/opslead/bootstrap-swarm-cluster/pulls) with your contribution.

# Issues
If you encountered a problem running this project, you can file an [issue](https://github.com/opslead/bootstrap-swarm-cluster/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Output of ansible 