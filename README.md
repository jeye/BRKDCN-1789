This git is for CiscoLive 2020 Barcelona BRKDCN-1789

Command to run playbook 1:
`ansible-playbook -i hosts --extra-vars "username=YOUR_APIC_USERNAME password=YOUR_APIC_PASSWORD" play1.yml -vv`

Command to run playbook 2:
`ansible-playbook -i hosts --extra-vars "username=YOUR_APIC_USERNAME password=YOUR_APIC_PASSWORD bigip_username=YOUR_BIGIP_ADMIN bigip_password=YOUR_BIGIP_PASSWORD" play2.yml -vv`

Command to run playbook 3:
`ansible-playbook -i hosts --extra-vars "username=YOUR_APIC_USERNAME password=YOUR_APIC_PASSWORD bigip_username=YOUR_BIGIP_ADMIN bigip_password=YOUR_BIGIP_PASSWORD" play3.yml -vv`

Command to run playbook 4:
`ansible-playbook -i hosts --extra-vars "username=YOUR_APIC_USERNAME password=YOUR_APIC_PASSWORD bigip_username=YOUR_BIGIP_ADMIN bigip_password=YOUR_BIGIP_PASSWORD" play4.yml -vv`

Command to run playbook master-play:
`ansible-playbook -i hosts --extra-vars "username=YOUR_APIC_USERNAME password=YOUR_APIC_PASSWORD bigip_username=YOUR_BIGIP_ADMIN bigip_password=YOUR_BIGIP_PASSWORD" master-play.yml -vv`
