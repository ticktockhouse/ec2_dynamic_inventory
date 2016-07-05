# ec2_dynamic_inventory

Doctored ec2 dynamic inventory code.

There are some pull requests kicking about which allow the ec2.py script to use the actual hostnames (or more specifically the "Name" tag) of the ec2 instances.

I have hacked the files in the standard ansible distribution and am hosting them here for convenience. Please let me know if there are any licensing concerns associated with this.

The PRs in question are: [here](https://github.com/ansible/ansible/pull/7395) and [here](https://github.com/ansible/ansible/pull/15526/commits/413afa74e7436b04ea136242b97c20d9109ecb59)
