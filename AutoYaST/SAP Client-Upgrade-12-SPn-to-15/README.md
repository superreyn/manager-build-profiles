Use this script as the basis for an upgrade from SLE 12 SPn to SLE 15 SPn.
Check the official product documentation to find the supported upgrade paths.

Important field on the Profile page:
Kernel options:  autoupgrade=1 insecure=1 useonlinerepo 

Variables tab for the Profile:

registration_key=<<activation_key>>

org=<<org_id>>

distrotree=<<distribution_label>>

channel_prefix=<<clm_channel_prefix>>
