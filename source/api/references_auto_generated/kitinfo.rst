.. _api_reference_kitinfo:

Kit Info  Resource
==================

| Resource URL ``http://mytorrentserver/rundb/api/v1/kitinfo/``
| Schema URL ``http://mytorrentserver/rundb/api/v1/kitinfo/schema/``
| 

.. include:: ../references_manual_extras/kitinfo.rst

Resource Fields
---------------

============================================ ================================================================================================== ======= ======== ======== ===== ====== ======= 
field                                        help text                                                                                          default nullable readonly blank unique type    
============================================ ================================================================================================== ======= ======== ======== ===== ====== ======= 
**isActive**                                 Boolean data. Ex: True                                                                             true    false    false    true  false  boolean 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**samplePrep_instrumentType**                Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**kitType**                                  Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**defaultFlowOrder**                         A single related resource. Can be either a URI or set of nested resource data.                     n/a     true     false    false false  related 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**name**                                     Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false true   string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**nucleotideType**                           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**defaultCartridgeUsageCount**               Integer data. Ex: 2673                                                                             n/a     true     false    false false  integer 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**instrumentType**                           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**chipTypes**                                Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**runMode**                                  Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**parts**                                    Many related resources. Can be either a list of URIs or list of individually nested resource data. n/a     false    false    false false  related 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**flowCount**                                Integer data. Ex: 2673                                                                             n/a     false    false    false false  integer 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**applicationType**                          Unicode string data. Ex: "Hello World"                                                                     true     false    false false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**cartridgeExpirationDayLimit**              Integer data. Ex: 2673                                                                             n/a     true     false    false false  integer 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**libraryReadLength**                        Integer data. Ex: 2673                                                                             0       false    false    false false  integer 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**cartridgeBetweenUsageAbsoluteMaxDayLimit** Integer data. Ex: 2673                                                                             n/a     true     false    false false  integer 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**resource_uri**                             Unicode string data. Ex: "Hello World"                                                             n/a     false    true     false false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**uid**                                      Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false true   string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**id**                                       Integer data. Ex: 2673                                                                                     false    false    true  true   integer 
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**categories**                               Unicode string data. Ex: "Hello World"                                                                     true     false    false false  string  
-------------------------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ ------- 
**description**                              Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string  
============================================ ================================================================================================== ======= ======== ======== ===== ====== ======= 

Example Response
^^^^^^^^^^^^^^^^

.. code-block:: javascript

	{
	    "meta": {
	        "previous": null, 
	        "total_count": 114, 
	        "offset": 0, 
	        "limit": 1, 
	        "next": "/rundb/api/v1/kitinfo/?offset=1&limit=1&format=json"
	    }, 
	    "objects": [
	        {
	            "isActive": false, 
	            "samplePrep_instrumentType": "", 
	            "kitType": "ControlSequenceKit", 
	            "defaultFlowOrder": null, 
	            "name": "Ion PGM Controls Kit v2", 
	            "nucleotideType": "", 
	            "defaultCartridgeUsageCount": null, 
	            "instrumentType": "pgm", 
	            "chipTypes": "", 
	            "runMode": "", 
	            "parts": [
	                {
	                    "barcode": "4482010", 
	                    "id": 20072, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20072/", 
	                    "kit": "/rundb/api/v1/kitinfo/20037/"
	                }, 
	                {
	                    "barcode": "4482011", 
	                    "id": 20073, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20073/", 
	                    "kit": "/rundb/api/v1/kitinfo/20037/"
	                }
	            ], 
	            "flowCount": 0, 
	            "applicationType": "", 
	            "cartridgeExpirationDayLimit": null, 
	            "libraryReadLength": 0, 
	            "cartridgeBetweenUsageAbsoluteMaxDayLimit": null, 
	            "resource_uri": "/rundb/api/v1/kitinfo/20037/", 
	            "uid": "CONSEQ0003", 
	            "id": 20037, 
	            "categories": "", 
	            "description": "Ion PGM Controls Kit v2"
	        }
	    ]
	}

Allowed list HTTP methods
-------------------------

- GET
- POST
- PUT
- DELETE
- PATCH


Allowed detail HTTP methods
---------------------------

- GET
- POST
- PUT
- DELETE
- PATCH

