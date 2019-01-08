# sfdx-bash-completion

Bash completion for the [sfdx cli](https://developer.salesforce.com/tools/sfdxcli) and the [force cli](https://developer.salesforce.com/tools/forcecli).

**This is a work in progress**

Right now it supports the action, the help parameter and the -u or --targetusername parameter.

To be able to support aliases for users the `jq` command is required.

## installation

place `sfdx` and `force` in `/etc/bash_completion.d/`
