# ansible


-  4 linux machines (VMs, instances in Digital Ocean, GCP, AWS EC2, dosen't matter);
-  Python installed (2.7 or 3.5+);
-  established password-less connection from one machine (controller) to others;

#Task


Create a inventory file with four groups, each provisioning VM should be in separate group and group named iaas what should include childrens from two first groups;


- Create reusable roles for that:
- creating a empty file /etc/iaac with rigths 0500, this role should be idempodent
- define content of /etc/issue as variable


- Create playbook for:
- invoke the role for /etc/iaac for hosts group iaas
- invoke the role for defining variable for all hosts
- print in registered variables
- printing hostnames together with registered variables will be a plus.
- Create a repo in your GitHub account and commit code above



https://stackoverflow.com/questions/57656073/how-to-set-different-python-interpreters-for-local-and-remote-hosts
