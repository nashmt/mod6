# Choice of Provisioning tool
# Status: accepted
# Context:
For Assignment 6, we were required to produce a working application that utilized ansible-playbook instead of docker-compose.
# Decision:
I choose to use Ansible to follow assignment guidelines.
# Consequences:
Ansible is a useful tool for a variety of reasons. It can be used for provisioning IoT devices or server infrastructure, configure applications, and deployment. It also easily manages versions of your applications and lets you revert if necessary. Additionally, servers, daemons, and databases are not required -- all that you need is Ansible on a host machine and Python on the target machines with SSH access. That means there is no need for the targets to have any special software to run your app. Furthermore, Ansible will only run tasks in your playbooks if needed.
I am able to use Ansible to provision the application by creating tasks in a simple YAML file. I start by building the necessary Docker images for my containers. Then I launch the database container and load in the data if necessary. Finally, I launch the last two containers and configure them to use ZMQ to communicate with the database.
