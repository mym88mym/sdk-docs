Experiment Resource
==========================================================================

Resource URL: ``http://mytorrentserver/rundb/api/v1/experiment/``


Schema URL: ``http://mytorrentserver/rundb/api/v1/experiment/schema/``


.. include:: ../manual_api_ref_docs/experiment.rst

Fields table
------------

=========================== ================================================================================================== ======= ======== ======== ===== ====== ======== 
field                       help text                                                                                          default nullable readonly blank unique type     
=========================== ================================================================================================== ======= ======== ======== ===== ====== ======== 
**isReverseRun**            Boolean data. Ex: True                                                                             false   false    false    true  false  boolean  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefLotNumber**           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chipType**                Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**user_ack**                Unicode string data. Ex: "Hello World"                                                             U       false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefLogPath**             Unicode string data. Ex: "Hello World"                                                             n/a     true     false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**results**                 Many related resources. Can be either a list of URIs or list of individually nested resource data. n/a     false    false    false false  related  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefSolutionsPart**       Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**runtype**                 Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefLastUpdate**          A date & time as a string. Ex: "2010-11-10T03:07:43"                                               n/a     true     false    false false  datetime 
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**storage_options**         Unicode string data. Ex: "Hello World"                                                             A       false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefChipExpiration1**     Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefChipExpiration2**     Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**diskusage**               Integer data. Ex: 2673                                                                             n/a     true     false    false false  integer  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefStatus**              Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**reverse_primer**          Unicode string data. Ex: "Hello World"                                                             n/a     true     false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**seqKitBarcode**           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**id**                      Integer data. Ex: 2673                                                                                     false    false    true  true   integer  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefReagentsPart**        Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**metaData**                Unicode string data. Ex: "Hello World"                                                             {}      false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefInstrumentName**      Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**sample**                  Unicode string data. Ex: "Hello World"                                                             n/a     false    true     true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**log**                     Unicode string data. Ex: "Hello World"                                                             {}      false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**sequencekitbarcode**      Unicode string data. Ex: "Hello World"                                                             n/a     true     false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**resource_uri**            Unicode string data. Ex: "Hello World"                                                             n/a     false    true     false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**eas_set**                 Many related resources. Can be either a list of URIs or list of individually nested resource data. n/a     true     false    true  false  related  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefReagentID**           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**platform**                Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefScriptVersion**       Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**samples**                 Many related resources. Can be either a list of URIs or list of individually nested resource data. n/a     true     false    true  false  related  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefManufactureDate**     Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefSamplePos**           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**pinnedRepResult**         Boolean data. Ex: True                                                                             false   false    false    true  false  boolean  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefReagentsExpiration**  Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefSolutionsLot**        Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**reagentBarcode**          Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefProgress**            Floating point numeric data. Ex: 26.73                                                             0       false    false    true  false  float    
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefKitType**             Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**star**                    Boolean data. Ex: True                                                                             false   false    false    true  false  boolean  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefPackageVer**          Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**isProton**                Unicode string data. Ex: "Hello World"                                                             n/a     false    true     false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**expCompInfo**             Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**flowsInOrder**            Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**flows**                   Integer data. Ex: 2673                                                                             n/a     false    false    false false  integer  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**resultDate**              A date & time as a string. Ex: "2010-11-10T03:07:43"                                               true    true     false    false false  datetime 
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefTipRackBarcode**      Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**plan**                    A single related resource. Can be either a URI or set of nested resource data.                     n/a     true     false    true  false  related  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**date**                    A date & time as a string. Ex: "2010-11-10T03:07:43"                                               n/a     false    false    false false  datetime 
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefExtraInfo_1**         Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefExtraInfo_2**         Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**unique**                  Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false true   string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**expDir**                  Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**autoAnalyze**             Boolean data. Ex: True                                                                             true    false    false    true  false  boolean  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**ftpStatus**               Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefMessage**             Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**cycles**                  Integer data. Ex: 2673                                                                             n/a     false    false    false false  integer  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**displayName**             Unicode string data. Ex: "Hello World"                                                                     false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**runMode**                 Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**notes**                   Unicode string data. Ex: "Hello World"                                                             n/a     true     false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**sequencekitname**         Unicode string data. Ex: "Hello World"                                                             n/a     true     false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chipBarcode**             Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**pgmName**                 Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefSolutionsExpiration** Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefReagentsLot**         Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**storageHost**             Unicode string data. Ex: "Hello World"                                                             n/a     true     false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**expName**                 Unicode string data. Ex: "Hello World"                                                             n/a     false    false    false false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**status**                  Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**usePreBeadfind**          Boolean data. Ex: True                                                                             true    false    false    true  false  boolean  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefChipType2**           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**chefChipType1**           Unicode string data. Ex: "Hello World"                                                                     false    false    true  false  string   
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**baselineRun**             Boolean data. Ex: True                                                                             false   false    false    true  false  boolean  
--------------------------- -------------------------------------------------------------------------------------------------- ------- -------- -------- ----- ------ -------- 
**rawdatastyle**            Unicode string data. Ex: "Hello World"                                                             single  true     false    false false  string   
=========================== ================================================================================================== ======= ======== ======== ===== ====== ======== 

Example request
---------------

Request URL: ``http://mytorrentserver/rundb/api/v1/experiment/?format=json&limit=1``


Python example
^^^^^^^^^^^^^^

.. code-block:: python

	
	import requests
	
	ts_api_request = requests.get("http://mytorrentserver/rundb/api/v1/experiment/", params={"format": "json", "limit": 1})
	ts_api_response = ts_api_request.json()
	
	experiments = ts_api_response["objects"]
	
	for experiment in experiments:
	    print experiment
	
Torrent Server response
^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: javascript

	{
	    "meta": {
	        "previous": null, 
	        "total_count": 87, 
	        "offset": 0, 
	        "limit": 1, 
	        "next": "/rundb/api/v1/experiment/?offset=1&limit=1&format=json"
	    }, 
	    "objects": [
	        {
	            "isReverseRun": false, 
	            "chefLotNumber": "", 
	            "chipType": "", 
	            "user_ack": "U", 
	            "chefLogPath": null, 
	            "results": [], 
	            "chefSolutionsPart": "", 
	            "runtype": "GENS", 
	            "chefLastUpdate": null, 
	            "storage_options": "A", 
	            "chefChipExpiration1": "", 
	            "chefChipExpiration2": "", 
	            "diskusage": null, 
	            "chefStatus": "", 
	            "reverse_primer": null, 
	            "seqKitBarcode": "", 
	            "id": 3, 
	            "chefReagentsPart": "", 
	            "metaData": {}, 
	            "chefInstrumentName": "", 
	            "sample": "", 
	            "log": {}, 
	            "sequencekitbarcode": "", 
	            "resource_uri": "/rundb/api/v1/experiment/3/", 
	            "eas_set": [
	                {
	                    "ionstatsargs": "", 
	                    "isEditable": true, 
	                    "hotSpotRegionBedFile": "", 
	                    "results": [], 
	                    "mixedTypeRNA_reference": null, 
	                    "mixedTypeRNA_targetRegionBedFile": null, 
	                    "targetRegionBedFile": "", 
	                    "thumbnailalignmentargs": "", 
	                    "thumbnailanalysisargs": "", 
	                    "id": 3, 
	                    "barcodedSamples": {}, 
	                    "base_recalibration_mode": "standard_recal", 
	                    "reference": "e_coli_dh10b", 
	                    "isOneTimeOverride": false, 
	                    "mixedTypeRNA_hotSpotRegionBedFile": null, 
	                    "analysisargs": "", 
	                    "thumbnailcalibrateargs": "", 
	                    "realign": false, 
	                    "selectedPlugins": {}, 
	                    "experiment": "/rundb/api/v1/experiment/3/", 
	                    "barcodeKitName": "", 
	                    "beadfindargs": "", 
	                    "threePrimeAdapter": "ATCACCGACTGCCCATAGAGAGGCTGAGAC", 
	                    "thumbnailbasecallerargs": "", 
	                    "status": "planned", 
	                    "prebasecallerargs": "", 
	                    "thumbnailionstatsargs": "", 
	                    "prethumbnailbasecallerargs": "", 
	                    "alignmentargs": "", 
	                    "isDuplicateReads": false, 
	                    "libraryKey": "TCAG", 
	                    "date": "2017-03-08T16:27:32.000781+00:00", 
	                    "libraryKitName": "Ion Xpress Plus Fragment Library Kit", 
	                    "thumbnailbeadfindargs": "", 
	                    "calibrateargs": "", 
	                    "tfKey": "ATCG", 
	                    "libraryKitBarcode": null, 
	                    "sseBedFile": "", 
	                    "basecallerargs": "", 
	                    "custom_args": false, 
	                    "resource_uri": "/rundb/api/v1/experimentanalysissettings/3/"
	                }
	            ], 
	            "chefReagentID": "", 
	            "platform": "PGM", 
	            "chefScriptVersion": "", 
	            "samples": [], 
	            "chefManufactureDate": "", 
	            "chefSamplePos": "", 
	            "pinnedRepResult": false, 
	            "chefReagentsExpiration": "", 
	            "chefSolutionsLot": "", 
	            "reagentBarcode": "", 
	            "chefProgress": 0, 
	            "chefKitType": "", 
	            "star": false, 
	            "chefPackageVer": "", 
	            "isProton": "False", 
	            "expCompInfo": "", 
	            "flowsInOrder": "", 
	            "flows": 500, 
	            "resultDate": "2017-03-08T16:24:27.000296+00:00", 
	            "chefTipRackBarcode": "", 
	            "plan": "/rundb/api/v1/plannedexperiment/22/", 
	            "date": "2017-03-08T16:24:27.000295+00:00", 
	            "chefExtraInfo_1": "", 
	            "chefExtraInfo_2": "", 
	            "unique": "ad416288-d7b1-49e6-bb63-f7459e824b21", 
	            "expDir": "", 
	            "autoAnalyze": true, 
	            "ftpStatus": "Complete", 
	            "chefMessage": "", 
	            "cycles": 0, 
	            "displayName": "0ZQVQ", 
	            "runMode": "single", 
	            "notes": "", 
	            "sequencekitname": "IonPGM200Kit-v2", 
	            "chipBarcode": "", 
	            "pgmName": "", 
	            "chefSolutionsExpiration": "", 
	            "chefReagentsLot": "", 
	            "storageHost": "", 
	            "expName": "ad416288-d7b1-49e6-bb63-f7459e824b21", 
	            "status": "planned", 
	            "usePreBeadfind": false, 
	            "chefChipType2": "", 
	            "chefChipType1": "", 
	            "baselineRun": false, 
	            "rawdatastyle": "single"
	        }
	    ]
	}

Allowed HTTP methods
--------------------

- get
- post
- put
- delete
- patch

