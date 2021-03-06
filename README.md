# CRD examples for the Red Hat Single Sign-On Operator

## Prerequisites

You will need:

- Openshift 4.6+ up and running
- A new openshift project
- The Red Hat Single Sign-On Operator installed ([click here the instructions](https://access.redhat.com/documentation/en-us/red_hat_single_sign-on/7.6/html/server_installation_and_configuration_guide/operator#installing-operator))

## Keycloak instance CRD 
- [example-instance.yml](example-instance.yml)

## Keycloak realm CRD
- [example-realm.yml](example-realm.yml)
- [pam-realm.yml](pam-realm.yml)

## Keycloak client CRD
- [pam-bc-client.yml](pam-bc-client.yml)
- [pam-ks-client.yml](pam-ks-client.yml)

## Keycloak user CRD
- [example-user.yml](example-user.yml)
- [pam-admin-user.yml](pam-admin-user.yml)

## other examples
- [https://github.com/keycloak/keycloak-operator/tree/main/deploy/examples](https://github.com/keycloak/keycloak-operator/tree/main/deploy/examples)