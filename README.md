# Learning Ansible 2.7 - Third Edition

<a href="https://www.packtpub.com/networking-and-servers/learning-ansible-27-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789954333"><img src="https://dz13w8afd47il.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/MoCoverB12951.png" alt="Learning Ansible 2.7 - Third Edition" height="256px" align="right"></a>

This is the code repository for [Learning Ansible 2.7 - Third Edition](https://www.packtpub.com/networking-and-servers/learning-ansible-27-third-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789954333), published by Packt.

**Use Ansible to configure your systems, deploy software, and orchestrate advanced IT tasks**

## What is this book about?
Ansible is an open source automation platform that assists organizations with tasks such as application deployment, orchestration, and task automation. With the release of Ansible 2.7, even complex tasks can be handled much more easily than before.

This book covers the following exciting features:
* Create a web server using Ansible 
* Write a custom module and test it 
* Deploy playbooks in the production environment 
* Troubleshoot networks using Ansible 
* Use Ansible Galaxy and Ansible Tower during deployment 

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1789954339) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
- hosts: all
remote_user: vagrant
tasks:
- name: Ensure the HTTPd package is installed
yum:
name: httpd
state: present
become: True
```

**Following is what you need for this book:**
This beginner-level book is for system administrators who want to automate their organization's infrastructure using Ansible 2.7. No prior knowledge of Ansible is required

With the following software and hardware list you can run all code files present in the book (Chapter 1-12).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-12 | Ansible | UNIX |
| 1-10 | Vagrant | - |
| 11-12 | AWX | Docker |

### Related products
* Mastering Ansible - Third Edition  [[Packt]](https://prod.packtpub.com/in/virtualization-and-cloud/mastering-ansible-third-edition?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1789951542)

* Ansible 2 Cloud Automation Cookbook  [[Packt]](https://prod.packtpub.com/in/virtualization-and-cloud/ansible-2-cloud-automation-cookbook?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/178829582X)


## Get to Know the Author
**Fabio Alessandro Locati**
commonly known as Fale, is a director at Otelia, a public speaker, an author, and an open source contributor. His main areas of expertise are Linux, automation, security, and cloud technologies. Fale has more than 12 years of working experience in IT, with many of them spent consulting for many companies, including dozens of Fortune 500 companies. This has allowed him to consider technologies from different points of view, and to think critically about them.

## Other books by the authors
[OpenStack Cloud Security](https://www.packtpub.com/virtualization-and-cloud/openstack-cloud-security?utm_source=github&utm_medium=repository&utm_campaign=9781782170983 )

[Learning Ansible 2 - Second Edition](https://www.packtpub.com/networking-and-servers/learning-ansible-2-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786464231 )


### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.


