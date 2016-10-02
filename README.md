ansible-gcloud role
===================

Installs gcloud SDK

See https://cloud.google.com/sdk/docs/

Variables
---------

Variables can be obtained from an account service key, which can be
created at
https://console.cloud.google.com/iam-admin/serviceaccounts/project?project=youproject

Then create a service account, generate a JSON key, and fill the
following variables:

- `gcloud_service_email`: email associated to the service account
- `gcloud_project_id`: project ID (google console project)
- `gcloud_client_id`: client ID, found in JSON service key
- `gcloud_private_key`: private key, on a single line using \n (e.g. "-----BEGIN PRIVATE
  KEY-----\nSDFSDSFD\nSDFFSDFD..."), found in JSON service key
- `gcloud_private_key_id`: private key id found in JSON service key

All these variables are compulsory !

Michel Blanc <mb@mbnet.fr>
