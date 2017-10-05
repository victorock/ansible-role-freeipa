# Ansible Role: FreeIPA Server

Installs FreeIPA on any RedHat/CentOS.


freeipa_admin_password: "_Fr331P4_"

freeipa_hostname: "{{ ansible_fqdn }}"

freeipa_ipv4_address: "{{ ansible_eth0.ipv4.address }}"

freeipa_domain: "acme.com"

freeipa_forwarder_primary: "8.8.8.8"

freeipa_forwarder_secondary: "8.8.4.4"

freeipa_firewall_state: started

## License

MIT / BSD

## Author Information
