# Kustomization for Deploying Red Hat Single Sign-On (RHSSO) on OpenShift

Red Hat Single Sign-On production documentation can be found [here](https://access.redhat.com/documentation/en-us/red_hat_single_sign-on). RHSSO operator is documented in [The Red Hat Single Sign-On Operator](https://access.redhat.com/documentation/en-us/red_hat_single_sign-on/7.4/html/server_installation_and_configuration_guide/operator). RHSSO operator is based on [keycloak-operator](https://github.com/keycloak/keycloak-operator).

## Quick Start

```
$ oc apply --kustomize rhsso-operator/base
```

```
$ oc apply --kustomize rhsso-instance/base
```
