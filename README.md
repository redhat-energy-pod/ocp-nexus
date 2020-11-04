# ocp-nexus

Install Operator

`oc apply -k https://github.com/redhat-energy-pod/ocp-nexus/operator`

Install Instance

`oc apply -k https://github.com/redhat-energy-pod/ocp-nexus/instance`

It takes a few minutes for the UI to come up...

- Log into the UI at http://nexus3-nexus.apps.ocp.yourdomain.com with the default user (admin/admin123)
- Disable anonymous access
- Update the default users password