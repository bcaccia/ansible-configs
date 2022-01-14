# Prerequisites

On Fedora:
`sudo dnf install ansible ansible-collection-community-general`

On Ubuntu:
`sudo add-apt-repository --yes --update ppa:ansible/ansible; sudo apt install ansible`

On Manjaro:
`sudo pamac install ansible ansible-collection-community-general`

# Running Playbooks

`ansible-playbook -K ~/local.yml`
