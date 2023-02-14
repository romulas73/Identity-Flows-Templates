# Create Service Account Flow
The use case for this flow is this: Customer wanted to allow Server Administrators the ability to request a new service account in AD and Select the Safe that they want to store the new service account in. The Flow Post the message to a secure Slack channel. Once approveded the account will be created in Cyberark Identity and if you have AD Provisioning turned on it will create the account in AD. Then store the credentials in the selected safe.

## Configuration Steps

  1. Import the Flow
  2. Configure Authorizations for Slack
  3. Configure Authorizations for Identity
  4. Configure Authorizations for CorePAS
  5. Configure the Hostname for all connectors
  6. In the Custom Values set your Identity Tenant Suffix
  
