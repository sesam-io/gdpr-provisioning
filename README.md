This repo contains various files for manually provisioning a gdpr portal box.
(This repo will eventually be obsoleted when the provisioning is done automatically.)

To provision a new gdpr-portal, do the following:
  * Provision a new subscription in the sesam portal.
  * In the sesam-portal, add these secrets:
       
       email_server_password
       
       twilio-account-number
       
       twilio-api-token
        
  * Ssh to the new box and run these commands:

       git clone https://github.com/sesam-io/gdpr-provisioning.git
       
       cd gdpr-provisioning
       
       sudo ./provision.sh
  


