# shib-idp-conftree

## Purpose

This branch contains the default configuration tree (structure) for Shibboleth IDP.  The are various usage scenarios throughout the build, test, deploy cycle that warrant this abstraction
of the configuration tree.  There is a separate repository for the Docker Image which is responsible for building the runtime environment and pulling the configuration trees housed here
to complete a deployment.

### Configuration Trees

  * `default` branch
    * Comparison - (Default) branch/repo that is created by the Shibboleth IdP installer.  It is used for comparing the other branches.
  * `test` branch
    * Internal Testing - (TEST) branch/repo that uses the "test bed" which is something that I2 provides (LDAP) and an element to make all integrations.  Appropriate for Jenkins and testing environments
  * `release` branch
    * External Testing - (RELEASE) branch/repo (ultimately will live in Subversion?) for end users

