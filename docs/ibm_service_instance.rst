
ibm_service_instance -- Configure IBM Cloud 'ibm_service_instance' resource
===========================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_service_instance' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.6
- Terraform v0.12.20



Parameters
----------

  space_guid (False, str, None)
    (Required for new resource) The guid of the space in which the instance will be created


  service (False, str, None)
    (Required for new resource) The name of the service offering like speech_to_text, text_to_speech etc


  credentials (False, dict, None)
    The service broker-provided credentials to use this service.


  service_plan_guid (False, str, None)
    The uniquie identifier of the service offering plan type


  plan (False, str, None)
    (Required for new resource) The plan type of the service


  name (False, str, None)
    (Required for new resource) A name for the service instance


  service_keys (False, list, None)
    The service keys asociated with the service instance


  parameters (False, dict, None)
    Arbitrary parameters to pass along to the service broker. Must be a JSON object


  tags (False, list, None)
    None


  wait_time_minutes (False, int, 10)
    Define timeout to wait for the service instances to succeeded/deleted etc.


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

