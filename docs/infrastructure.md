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

## Misc notes
- DO = DigitalOcean
- SSH keys of server maintainers are stored in DO; server maintainers are invited to the 2HOL DO team.
- **Standard setup** As a rule, every new server should be created following [DO Initial Server Setup](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04) with the user "thol".
