# Ansible Role for Redhat SREP

Installs the tools Red Hat's SRE-P team uses to mange OpenShift.

## Requirements

Red Hat VPN access is required to install some tools.

## Role Variables

Variables are available to set the bin dir and versions of our tools to install.

```yaml
redhat_bin_dir: '~/.local/bin'
redhat_oc_version: 'stable'
redhat_ocm_version: '0.1.67'
redhat_backplane_version: '0.1.9'
redhat_osdctl_version: '0.17.0'
redhat_rosa_version: '1.2.23'
redhat_ocm_container_version: '0.2.0'
redhat_oc_nodepp_version: '0.1.1'
```

## Dependencies

None yet

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - roles:
         - { role: redhat-srep }

## License

Licensed under [Apache 2.0](https://opensource.org/licenses/Apache-2.0)
