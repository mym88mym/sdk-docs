.. _api_reference_availableonetouchplannedexperimentsummary:

Available Onetouch Planned Experiment Summary  Resource
=======================================================

| Resource URL ``http://mytorrentserver/rundb/api/v1/availableonetouchplannedexperimentsummary/``
| Schema URL ``http://mytorrentserver/rundb/api/v1/availableonetouchplannedexperimentsummary/schema/``
| 

.. include:: ../references_manual_extras/availableonetouchplannedexperimentsummary.rst

Resource Fields
---------------

=============================== ==================================================== ======= ======== ======== ===== ====== ======== 
field                           help text                                            default nullable readonly blank unique type     
=============================== ==================================================== ======= ======== ======== ===== ====== ======== 
**origin**                      Unicode string data. Ex: "Hello World"                       true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isReverseRun**                Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planDisplayedName**           Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**storage_options**             Unicode string data. Ex: "Hello World"               A       false    false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**preAnalysis**                 Boolean data. Ex: True                               true    false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planShortID**                 Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planStatus**                  Unicode string data. Ex: "Hello World"                       false    false    true  false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**runMode**                     Unicode string data. Ex: "Hello World"                       false    false    true  false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isCustom_kitSettings**        Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**sampleTubeLabel**             Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planExecutedDate**            A date & time as a string. Ex: "2010-11-10T03:07:43" n/a     true     false    false false  datetime 
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**samplePrepKitName**           Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**reverse_primer**              Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**seqKitBarcode**               Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**id**                          Integer data. Ex: 2673                                       false    false    true  true   integer  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**metaData**                    Unicode string data. Ex: "Hello World"               {}      false    false    true  false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isFavorite**                  Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**samplePrepProtocol**          Unicode string data. Ex: "Hello World"                       true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isPlanGroup**                 Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**templatingKitName**           Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**runType**                     Unicode string data. Ex: "Hello World"               GENS    false    false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**templatingKitBarcode**        Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planPGM**                     Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isSystemDefault**             Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**autoName**                    Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isReusable**                  Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**controlSequencekitname**      Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**date**                        A date & time as a string. Ex: "2010-11-10T03:07:43" n/a     true     false    false false  datetime 
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isSystem**                    Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**libkit**                      Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**categories**                  Unicode string data. Ex: "Hello World"                       true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planName**                    Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**pairedEndLibraryAdapterName** Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**adapter**                     Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**irworkflow**                  Unicode string data. Ex: "Hello World"                       false    false    true  false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planExecuted**                Boolean data. Ex: True                               false   false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**username**                    Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**usePostBeadfind**             Boolean data. Ex: True                               true    false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**storageHost**                 Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**expName**                     Unicode string data. Ex: "Hello World"                       false    false    true  false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**libraryReadLength**           Integer data. Ex: 2673                               0       false    false    false false  integer  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**runname**                     Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**usePreBeadfind**              Boolean data. Ex: True                               true    false    false    true  false  boolean  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**planGUID**                    Unicode string data. Ex: "Hello World"               n/a     true     false    false false  string   
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**cycles**                      Integer data. Ex: 2673                               n/a     true     false    false false  integer  
------------------------------- ---------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**resource_uri**                Unicode string data. Ex: "Hello World"               n/a     false    true     false false  string   
=============================== ==================================================== ======= ======== ======== ===== ====== ======== 

Example Response
^^^^^^^^^^^^^^^^

.. code-block:: javascript

	{
	    "meta": {
	        "previous": null, 
	        "total_count": 1, 
	        "offset": 0, 
	        "limit": 1, 
	        "next": null
	    }, 
	    "objects": [
	        {
	            "origin": "gui|5.8.0", 
	            "isReverseRun": false, 
	            "planDisplayedName": "Ion ReproSeq Aneuploidy - Ion PGM System", 
	            "storage_options": "A", 
	            "preAnalysis": true, 
	            "planShortID": "6TGIO", 
	            "planStatus": "planned", 
	            "runMode": "single", 
	            "isCustom_kitSettings": false, 
	            "sampleTubeLabel": "", 
	            "planExecutedDate": null, 
	            "samplePrepKitName": null, 
	            "reverse_primer": null, 
	            "seqKitBarcode": null, 
	            "id": 131, 
	            "metaData": {
	                "fromTemplate": "Ion_ReproSeq_Aneuploidy_-_Ion_PGM_System", 
	                "fromTemplateSource": "ION"
	            }, 
	            "isFavorite": false, 
	            "samplePrepProtocol": "", 
	            "isPlanGroup": false, 
	            "templatingKitName": "Ion PGM Template IA Tech Access Kit", 
	            "runType": "WGNM", 
	            "templatingKitBarcode": null, 
	            "planPGM": null, 
	            "isSystemDefault": false, 
	            "autoName": null, 
	            "isReusable": false, 
	            "controlSequencekitname": null, 
	            "date": "2018-02-26T17:28:33.000588+00:00", 
	            "isSystem": false, 
	            "libkit": null, 
	            "categories": "repro", 
	            "planName": "Ion_ReproSeq_Aneuploidy_-_Ion_PGM_System", 
	            "pairedEndLibraryAdapterName": "", 
	            "adapter": null, 
	            "irworkflow": "", 
	            "planExecuted": false, 
	            "username": "ionadmin", 
	            "usePostBeadfind": true, 
	            "storageHost": null, 
	            "expName": "", 
	            "libraryReadLength": 0, 
	            "runname": null, 
	            "usePreBeadfind": true, 
	            "planGUID": "d1ed9718-b6f4-4dfd-8de5-bbd150092997", 
	            "cycles": null, 
	            "resource_uri": "/rundb/api/v1/availableonetouchplannedexperimentsummary/131/"
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

