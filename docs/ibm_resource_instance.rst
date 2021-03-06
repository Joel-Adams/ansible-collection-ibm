
ibm_resource_instance -- Configure IBM Cloud 'ibm_resource_instance' resource
=============================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_resource_instance' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.6
- Terraform v0.12.20



Parameters
----------

  parameters (False, dict, None)
    Arbitrary parameters to pass. Must be a JSON object


  status (False, str, None)
    Status of resource instance


  guid (False, str, None)
    Guid of resource instance


  service_endpoints (False, str, None)
    Types of the service endpoints. Possible values are 'public', 'private', 'public-and-private'.


  resource_crn (False, str, None)
    The crn of the resource


  service (False, str, None)
    (Required for new resource) The name of the service offering like cloud-object-storage, kms etc


  resource_group_id (False, str, None)
    The resource group id


  resource_name (False, str, None)
    The name of the resource


  resource_group_name (False, str, None)
    The resource group name in which resource is provisioned


  name (False, str, None)
    (Required for new resource) A name for the resource instance


  plan (False, str, None)
    (Required for new resource) The plan type of the service


  tags (False, list, None)
    None


  crn (False, str, None)
    CRN of resource instance


  resource_status (False, str, None)
    The status of the resource


  resource_controller_url (False, str, None)
    The URL of the IBM Cloud dashboard that can be used to explore and view details about the resource


  location (False, str, None)
    (Required for new resource) The location where the instance available


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to


  ibmcloud_zone (False, any, None)
    Denotes which IBM Cloud zone to connect to in multizone environment. This can also be provided via the environmental variable 'IC_ZONE'.













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

