# Ansible Works

This Repo has some ansible yml scripts to automate routine tasks.

## rebuildstorage.yml
For Kubernetes master with several number of worker nodes, the docker containers dumps the nodes. To rebuild the docker node's storage this script will stop the running docker and storage services and rebuild them
