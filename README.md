# f5-reference solutions - General onboard for bigip, 
templates, hardening, default profiles  creates logging profiles, dosl7 profile 


# Summary

ansible-playbook --vault-password-file ~/.vault_pass.txt \
playbooks/bigip_general_onboarding.yaml -e "\
bigip_ip_addr="$(etcdctl get f5-rs-aws-tag-master/yossir100/master_ip_address)" \
bigip_mgmt_port=8443"




API:

input parameters:

bigip_mgmt_port
bigip_ip_addr

