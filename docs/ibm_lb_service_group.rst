
ibm_lb_service_group -- Configure IBM Cloud 'ibm_lb_service_group' resource
===========================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_lb_service_group' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.6
- Terraform v0.12.20



Parameters
----------

  load_balancer_id (False, int, None)
    (Required for new resource)


  port (False, int, None)
    (Required for new resource)


  routing_type (False, str, None)
    (Required for new resource)


  service_group_id (False, int, None)
    None


  allocation (False, int, None)
    (Required for new resource)


  routing_method (False, str, None)
    (Required for new resource)


  timeout (False, int, None)
    None


  tags (False, list, None)
    None


  virtual_server_id (False, int, None)
    None


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

