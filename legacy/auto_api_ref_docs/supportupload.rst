Supportupload Resource
==========================================================================

Resource URL: ``http://mytorrentserver/rundb/api/v1/supportupload/``


Schema URL: ``http://mytorrentserver/rundb/api/v1/supportupload/schema/``


.. include:: ../manual_api_ref_docs/supportupload.rst

Fields table
------------

================== ============================================================================== ======= ======== ======== ===== ====== ======== 
field              help text                                                                      default nullable readonly blank unique type     
================== ============================================================================== ======= ======== ======== ===== ====== ======== 
**ticket_id**      Unicode string data. Ex: "Hello World"                                                 false    false    true  false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**updated**        A date & time as a string. Ex: "2010-11-10T03:07:43"                           true    false    false    true  false  datetime 
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**local_message**  Unicode string data. Ex: "Hello World"                                                 false    false    true  false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**description**    Unicode string data. Ex: "Hello World"                                                 false    false    false false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**created**        A date & time as a string. Ex: "2010-11-10T03:07:43"                           true    false    false    true  false  datetime 
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**ticket_status**  Unicode string data. Ex: "Hello World"                                                 false    false    true  false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**contact_email**  Unicode string data. Ex: "Hello World"                                                 false    false    false false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**result**         A single related resource. Can be either a URI or set of nested resource data. n/a     false    false    false false  related  
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**file**           A single related resource. Can be either a URI or set of nested resource data. n/a     true     false    false false  related  
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**celery_task_id** Unicode string data. Ex: "Hello World"                                                 false    false    true  false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**ticket_message** Unicode string data. Ex: "Hello World"                                                 false    false    true  false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**id**             Integer data. Ex: 2673                                                                 false    false    true  true   integer  
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**local_status**   Unicode string data. Ex: "Hello World"                                                 false    false    true  false  string   
------------------ ------------------------------------------------------------------------------ ------- -------- -------- ----- ------ -------- 
**resource_uri**   Unicode string data. Ex: "Hello World"                                         n/a     false    true     false false  string   
================== ============================================================================== ======= ======== ======== ===== ====== ======== 

Example request
---------------

Request URL: ``http://mytorrentserver/rundb/api/v1/supportupload/?format=json&limit=1``


Python example
^^^^^^^^^^^^^^

.. code-block:: python

	
	import requests
	
	ts_api_request = requests.get("http://mytorrentserver/rundb/api/v1/supportupload/", params={"format": "json", "limit": 1})
	ts_api_response = ts_api_request.json()
	
	supportuploads = ts_api_response["objects"]
	
	for supportupload in supportuploads:
	    print supportupload
	
Torrent Server response
^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: javascript

	{
	    "meta": {
	        "previous": null, 
	        "total_count": 0, 
	        "offset": 0, 
	        "limit": 1, 
	        "next": null
	    }, 
	    "objects": []
	}

Allowed HTTP methods
--------------------

- get
- post
- put
- delete
- patch

