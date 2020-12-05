# Infrastrucutre
Use this as a quick reference or a guide to duplicate this project.

## Quick details:
- **Hosting provider:** DigitalOcean (No particular reason)
- **DNS provider:** DigitalOcean
- **Domain registrar:** Namecheap
- **Email provider:** Namecheap (admin@twohoursonelife.com)

## Servers
### Ansible Controller & Jenkins
**aj.twohoursonelife.com**
- Responsible for hosting the Ansible controller and the Jenkins instance.
- Basic droplet ($5/month, 1vCPU, 1GB RAM, 25GB SSD, backups enabled).
- Standard setup
- [Ansible Controller Setup](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-18-04)
- [Jenkins Setup](https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-18-04)
- [Secure Jenkins](https://www.digitalocean.com/community/tutorials/how-to-configure-jenkins-with-ssl-using-an-nginx-reverse-proxy-on-ubuntu-18-04)

## Misc notes
- DO = DigitalOcean
- SSH keys of server maintainers are stored in DO; server maintainers are invited to the 2HOL DO team.
- **Standard setup**: As a rule, every new server should be created following [DO Initial Server Setup](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04) with the user "thol".
- Use SSH keys over passwords wherever possible, but where necessary:
- Passwords should be generated and stored using a password manager such as LastPass. Passwords should be 20 characters long and be alphanumeric.
