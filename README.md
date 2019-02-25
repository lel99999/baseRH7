# baseRH7
Base Image using RHEL 7 Subscription Management with Satellite Repos

### Sign up for RedHat Developer Subscription Account
Developer Portal (https://developers.redhat.com/)

Information regarding RedHat Developer Program (https://developers.redhat.com/blog/2016/03/31/no-cost-rhel-developer-subscription-now-available/)

### Use RedHat AccountID/Password for Ansible Scripts
Create a file under your home directory, say RHACCOUNT with the following key:value template <br/>
**For Added Security**: Consider encrypting this information using Ansible Vault

_uid:  <account_id @ redhat.com>  <br/>
_pwd:  <account_password>     <br/>
