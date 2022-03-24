# Upgrading to SLE15 SPn for SAP
Use this script as the basis for an upgrade from SLE 12 SPn SAP to SLE 15 SPn SAP.
Check the official product documentation to find the supported upgrade paths.

Be sure to sync all modules referenced in the profile.

# Important field on the Profile page:
Kernel options:  autoupgrade=1 insecure=1 useonlinerepo 

# Variables tab for the Profile:

registration_key=<<activation_key>>

org=<<org_id>>

distrotree=<<distribution_label>>

channel_prefix=<<clm_channel_prefix>>
