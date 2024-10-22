# Ansible Role: Docker Secrets
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Manage sensitive data with Docker secrets [Docs](https://docs.docker.com/engine/swarm/secrets/#read-more-about-docker-secret-commands)

Requirements
------------

Swarm Mode should be enabled on target.

Role Variables
--------------

List of secrets:

```
secrets:
  hello: "world"
```

Dependencies
------------

None.

Example Playbook
----------------


    $ cat inventory
    [servers]
    172.10.10.1

    $ cat playbook.yml
    - name: "Setup Docker Secrets"
      hosts: servers
      roles:
        - { role: mlabouardy.docker-secrets }
        
# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟