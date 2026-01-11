# ansible-playbook-AWS-Networks

Before we launch virtual machine instances, we must create a network to host them. This is called a virtual private cloud (VPC) and there are a few different elements we will need to bring together in a playbook to create one, which we will then be able to use for our instances.

```
$ export AWS_ACCESS_KEY=<access_key>
$ export AWS_SECRET_KEY=<secret_key>
$ ansible-playbook -i hosts site.yml
$ ansible-playbook -i hosts destroy.yml
```
