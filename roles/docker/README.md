# Docker role for the IoT testbed

iot_lab.docker

## Role description

Install Docker CE and Docker compose on the raspberry pi.

### Requirements
- Tested on Raspberry pi 4 
- Raspbian OS 



## Testing The Playbook

```bash
ansible-playbook -i tests/inventory.yml tests/main.yml
```