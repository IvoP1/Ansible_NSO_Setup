# Ansible role to deploy NSO

Simple ansible role to deploy NSO server on a remote machine

## Requirements

- Ansible
- Target machine must be a valid & reachable ansible host

## Usage

Clone this repository, and execute the playbook.

```bash
ansible-playbook -e "username=username password=password version=5.3" playbook.yml
```
Username and Password required to download NSO image from tail-f repository. 

Alternatively can use the option of copying over the image from the local machine.

## Example
![](Ansible_NSO_Setup.gif)

## Remarks
Code not maintained. 

For production use it is recommended to make use of Ansible Vault for any confidential information.
