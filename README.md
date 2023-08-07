
1. For "proxied" hosts, set:
    ```
    ansible_network_os=check_point.gaia.checkpoint_mgmt
    ansible_host=<mgmt_server>
    ```

2. Run playbook
    ```
    ansible-playbook -i hosts playbook.yml
    ```
