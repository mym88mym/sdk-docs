.. _api_reference_activeprotonsequencingkitinfo:

Active Proton Sequencing Kit Info  Resource
===========================================

| Resource URL ``http://mytorrentserver/rundb/api/v1/activeprotonsequencingkitinfo/``
| Schema URL ``http://mytorrentserver/rundb/api/v1/activeprotonsequencingkitinfo/schema/``
| 

.. include:: ../references_manual_extras/activeprotonsequencingkitinfo.rst

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
	        "total_count": 5, 
	        "offset": 0, 
	        "limit": 1, 
	        "next": "/rundb/api/v1/activeprotonsequencingkitinfo/?offset=1&limit=1&format=json"
	    }, 
	    "objects": [
	        {
	            "isActive": true, 
	            "samplePrep_instrumentType": "", 
	            "kitType": "SequencingKit", 
	            "defaultFlowOrder": null, 
	            "name": "ProtonI200Kit-v2", 
	            "nucleotideType": "", 
	            "defaultCartridgeUsageCount": null, 
	            "instrumentType": "proton", 
	            "chipTypes": "900;P1.0.19;P1.0.20;P1.1.17;P1.1.541;P1.2.18;P2.0.1;P2.1.1;P2.3.1", 
	            "runMode": "", 
	            "parts": [
	                {
	                    "barcode": "4485149", 
	                    "id": 20094, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20094/", 
	                    "kit": "/rundb/api/v1/kitinfo/20044/"
	                }, 
	                {
	                    "barcode": "4485521", 
	                    "id": 20095, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20095/", 
	                    "kit": "/rundb/api/v1/kitinfo/20044/"
	                }, 
	                {
	                    "barcode": "4484082", 
	                    "id": 20096, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20096/", 
	                    "kit": "/rundb/api/v1/kitinfo/20044/"
	                }, 
	                {
	                    "barcode": "4482282", 
	                    "id": 20078, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20078/", 
	                    "kit": "/rundb/api/v1/kitinfo/20044/"
	                }, 
	                {
	                    "barcode": "4482284", 
	                    "id": 20079, 
	                    "resource_uri": "/rundb/api/v1/kitpart/20079/", 
	                    "kit": "/rundb/api/v1/kitinfo/20044/"
	                }
	            ], 
	            "flowCount": 500, 
	            "applicationType": "", 
	            "cartridgeExpirationDayLimit": null, 
	            "libraryReadLength": 0, 
	            "cartridgeBetweenUsageAbsoluteMaxDayLimit": null, 
	            "resource_uri": "/rundb/api/v1/activeprotonsequencingkitinfo/20044/", 
	            "uid": "SEQ0012", 
	            "id": 20044, 
	            "categories": "readLengthDerivableFromFlows;", 
	            "description": "Ion PI Sequencing 200 Kit v2"
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

