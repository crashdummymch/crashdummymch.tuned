#Ansible Role: crashdummymch.tuned

Ansible role for managing tuned service  
Manages package tuned  
Manages service tuned  


#License:
GPLv3
#Dependencies:
none
#Usage:
role: tuned
#Variables Used:
tuned_package_name: 'tuned'  
tuned_package_state: 'present'  
tuned_service_name: 'tuned'  
tuned_service_state: 'started'  
tuned_service_enabled: 'yes'
tuned_config_dir: "/etc/tuned"  
tuned_daemon: '1'  
tuned_dynamic_tuning: '1'  
tuned_sleep_interval: '1'  
tuned_update_interval: '10'  
tuned_recommend_command: '1'  
