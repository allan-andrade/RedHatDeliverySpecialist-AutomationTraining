# RedHatDeliverySpecialist-AutomationTraining
Question and Answers for this Training

C = Correct Answer

#1
Which of the following statements is false?
 Ansible is the automation language that enables you to describe an end-to-end IT application environment through playbooks
 Ansible is the underlying automation engine that runs playbooks
 Ansible Tower is a framework that helps organizations control and manage their Ansible automation
C Ansible is an alternative source code management system that allows you to store and manage your code in repositories

#2
Which of the following is a drawback of Ansible?
 Ansible is human readable but too simplistic and does not allow overly complex functionality
 Ansible executes all tasks in order, which makes it very slow and not usable at a large scale
 Ansible needs every host it manages to have a specific agent running
C There is no particular drawback stated in this course

#3
Ansible is purely a configuration management system.
 TRUE
C FALSE

#4
Red Hat Ansible Automation Platform ships with over 1,800 tasks.
 TRUE
C FALSE

#5
Ansible can run with Windows as the control node.
 TRUE
C FALSE

#6
Ansible requires a Python agent on each managed host.
 TRUE
C FALSE

#7
Ansible Playbooks are developed in which format?
 Jinja2
 Python
C JSON
 YAML

#8
Which transport mechanism does Ansible use to communicate with Linux/Unix machines?
 awk
 RDP
 netcat
C SSH

#9
In a static inventory file, which of the following defines an inventory group named "webservers"?
C [webservers]
 webservers
 group[webservers]
 group:webservers

#10
Ad hoc commands can pass arguments to a module with the -a flag.
C TRUE
 FALSE

#11
Which of the following has the highest precedence for a variable?
 block var
 inventory var
C extra var
 role defaults var

#12
The lowest precedence for a variable is one created by set_fact.
 TRUE
C FALSE

#13
Variables can be passed to the ansible-playbook command with the -v flag.
 TRUE
C FALSE

#14
Facts are gathered by which module?
 facts
C setup
 metadata
 sysinfo

#15
In which order are a playbook's tasks executed?
 Reverse
C Sequential
 Random
 Any of the above

#16
Handlers that have been notified run once at the end of the play.
C TRUE
 FALSE

#17
Ansible Galaxy is a repository that contains this type of community written content:
 Tasks
 Modules
C Roles
 Playbooks

#18
Which of the following features is not provided by Ansible Tower?
 Role-based access control
C Playbook creator wizard
 Centralized logging
 RESTful API

#19
Ansible Tower requires a minimum of 4GB of RAM.
C TRUE
 FALSE

#20
Which of the following features is NOT a supported platform to run Ansible Tower?
 Red Hat Enterprise Linux 7.4
 CentOS 7.4
C Windows Server 2018
 Ubuntu 16.04 LTS

#21
An organization in Ansible Tower is a group of hosts belonging to a department.
 TRUE
C FALSE

#22
Which of the following represents credential types in Ansible Tower?
C Network credentials
 Database credentials
 Web server credentials
 All of the above

#23
Ansible Tower supports dynamic inventories.
C TRUE
 FALSE

#24
Job templates are wizards for creating tasks.
 TRUE
C FALSE

#25
Ansible Tower allows jobs to run on a schedule.
C TRUE
 FALSE

#26
Users can interact with Ansible Tower using this method:
 Web browser
 API
 CLI tool
C All of the above

#27
Ansible Tower supports clustered installations.
C TRUE
 FALSE

#28
Automation Analytics is a SaaS available from access.redhat.com
 TRUE
C FALSE

#29
Automation Analytics includes a visual dashboard, health notifications, and organizational statistics.
C TRUE
 FALSE

#30
Automation Analytics offers more capability in tracking than Ansible Tower.
C TRUE
 FALSE

#31
Which of the following are interactions within the Automation Services Catalog?
 Platforms
 Portfolios
 Products
C All of the above

#32
Networking modules execute on the Ansible control node.
C TRUE
 FALSE

#33
The setup module for gathering facts works with networking devices.
 TRUE
C FALSE

#34
You cannot gather facts from a Windows remote host.
C TRUE
 FALSE

#35
Which Python module must be installed on the Ansible control to connect with Red Hat OpenStack Platform (RHOSP)?
C openstacksdk
 boto
 Pyvmomi
 winrm

#36
Ansible modules, can easily provision Docker containers.
C TRUE
 FALSE


