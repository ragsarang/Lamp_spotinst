# Lamp_spotinst
## Lamp using spotinst
## Ansible playbook to setup a whole LAMP stack, PHP app is Wordpress and DB is MySQL-RDS.

### Step1: 
#### Create Mysql RDS

### Step2:
#### Run ansible playbook to perform prerequisites
<code> ansible-playbook site.yml <code>

### Step3: 
#### Create AMI of the client ec2 instance where the prerequisites are performed

### Step4:
#### Run spotinst playbook to create Elastigroup
<code> ansible-playbook Lamp_spotinst/roles/spotinst/roles/tasks/main.yml <code>
