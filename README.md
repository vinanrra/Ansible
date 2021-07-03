# Ansible Playbooks
    - Prometheus
    - Grafana with Docker (Simple)
    - LAMP (Simple installation)
# Usage:
## Syntax
    ansible-playbook --ask-become-pass ./Ansible/STACK/playbook.yml -e @./Ansible/STACK/vars.yml
## Example Usage
    ansible-playbook --ask-become-pass ./Ansible/Docker-Grafana/playbook.yml -e @./Ansible/Docker-Grafana/grafana-docker_vars.yml
