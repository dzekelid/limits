{
  "info": {
    "name": "AWS Storage Gateway Service API Update Bandwidth Rate Limit",
    "_postman_id": "abbd9c38-f2b4-475b-8ee3-a3615ccb68ab",
    "description": "Updates the bandwidth rate limits of a gateway.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Gateway",
      "item": [
        {
          "id": "ec59bcfe-9dce-4b8b-b2a1-2da182091df1",
          "name": "activateGateway",
          "request": {
            "url": "http://example.com/api/?Action=ActivateGateway?ActivationKey=ActivationKey&GatewayName=GatewayName&GatewayRegion=GatewayRegion&GatewayTimezone=GatewayTimezone&GatewayType=GatewayType&MediumChangerType=MediumChangerType&TapeDriveType=TapeDriveType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Activates the gateway you previously deployed on your host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7db3a673-81d7-4588-9b55-612558fdf535"
            }
          ]
        },
        {
          "id": "b7ffb7d7-93e1-49eb-bda4-f507f89cdf52",
          "name": "deleteGateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGateway?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "802f20f3-5ac4-4e60-b3d7-07da14dd1bdd"
            }
          ]
        },
        {
          "id": "23b7650d-b625-469b-ad50-d57118f7b096",
          "name": "describeGatewayInformation",
          "request": {
            "url": "http://example.com/api/?Action=DescribeGatewayInformation?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata about a gateway such as its name, network interfaces, configured\n         time zone, and the state (whether the gateway is running or not)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7b998c3-d6f4-4c4e-8ffd-d6c1a34f0ef4"
            }
          ]
        },
        {
          "id": "1ab51e35-6633-4731-ba33-6bf691434f13",
          "name": "disableGateway",
          "request": {
            "url": "http://example.com/api/?Action=DisableGateway?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables a gateway when the gateway is no longer functioning."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b04bb067-4440-4f96-a526-d6ca00220dbb"
            }
          ]
        },
        {
          "id": "3564a1b2-4bd5-45b2-b45a-2056842b0972",
          "name": "shutdownGateway",
          "request": {
            "url": "http://example.com/api/?Action=ShutdownGateway?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Shuts down a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77aa8d37-e8b3-40c0-b302-bf96f5cfea56"
            }
          ]
        },
        {
          "id": "fe6a5697-c47a-4ee0-b9fc-9d41a59490e3",
          "name": "startGateway",
          "request": {
            "url": "http://example.com/api/?Action=StartGateway?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a gateway that you previously shut down (see."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b4454df-c5df-49e2-964d-937c81f45f4c"
            }
          ]
        }
      ]
    },
    {
      "name": "Cache",
      "item": [
        {
          "id": "e9a8d441-7ba9-4829-94b5-246aa0234690",
          "name": "addCache",
          "request": {
            "url": "http://example.com/api/?Action=AddCache?DiskIds=DiskIds&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures one or more gateway local disks as cache for a cached-volume gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8a39543-7c28-45e5-b980-e38cf46ed913"
            }
          ]
        },
        {
          "id": "d7bfa733-52af-40f4-bec8-bc33a0964272",
          "name": "describeCache",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCache?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the cache of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8729d8c-05d0-4242-9dad-58d541c830fb"
            }
          ]
        },
        {
          "id": "e651147c-b3c6-41a1-8d1d-1b745d17fee9",
          "name": "resetCache",
          "request": {
            "url": "http://example.com/api/?Action=ResetCache?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets all cache disks that have encountered a error and makes the disks available\n         for reconfiguration as cache storage."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5e164a2-ce4f-40ac-97a0-6f91e590ec83"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "d820cef4-6147-4348-be86-23691eadbafc",
          "name": "addTagsToResource",
          "request": {
            "url": "http://example.com/api/?Action=AddTagsToResource?ResourceARN=ResourceARN&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds one or more tags to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "539237b8-0603-4eab-968e-0c9512a85034"
            }
          ]
        },
        {
          "id": "52024031-69ae-40ad-b2d5-f841ab7f66f9",
          "name": "listTagsForResource",
          "request": {
            "url": "http://example.com/api/?Action=ListTagsForResource?Limit=Limit&Marker=Marker&ResourceARN=ResourceARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the tags that have been added to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f1f45d0-3b5d-4260-bb9a-504837acabea"
            }
          ]
        },
        {
          "id": "d906daff-698e-4ecc-920b-2a6ad4004d73",
          "name": "removeTagsFromResource",
          "request": {
            "url": "http://example.com/api/?Action=RemoveTagsFromResource?ResourceARN=ResourceARN&TagKeys=TagKeys",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes one or more tags from the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0714566c-9303-43ca-bf89-4eda48575385"
            }
          ]
        }
      ]
    },
    {
      "name": "Upload Buffer",
      "item": [
        {
          "id": "40685135-f386-4a97-91af-552f199a8d6a",
          "name": "addUploadBuffer",
          "request": {
            "url": "http://example.com/api/?Action=AddUploadBuffer?DiskIds=DiskIds&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures one or more gateway local disks as upload buffer for a specified gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4aed8fb2-adf9-483c-a98a-2cfb4c152c92"
            }
          ]
        },
        {
          "id": "180e2a3b-e410-4c2a-8d4e-76097e7f4b46",
          "name": "describeUploadBuffer",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUploadBuffer?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the upload buffer of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "764f5227-bbb2-4e97-af76-4d40d0578e1d"
            }
          ]
        }
      ]
    },
    {
      "name": "Working Storage",
      "item": [
        {
          "id": "2e9b0af5-2a42-427a-a3d9-f5fb7adfb13b",
          "name": "addWorkingStorage",
          "request": {
            "url": "http://example.com/api/?Action=AddWorkingStorage?DiskIds=DiskIds&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures one or more gateway local disks as working storage for a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "753cbde6-8aaa-4f8e-920a-e0b7704ee9c9"
            }
          ]
        },
        {
          "id": "944c4e79-149b-4efd-a378-226221c4adf0",
          "name": "describeWorkingStorage",
          "request": {
            "url": "http://example.com/api/?Action=DescribeWorkingStorage?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the working storage of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4565a1c2-4bbd-46f7-ab83-27a57d3d81fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Archival",
      "item": [
        {
          "id": "d3559be3-417e-449c-a7ed-30d208e84074",
          "name": "cancelArchival",
          "request": {
            "url": "http://example.com/api/?Action=CancelArchival?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels archiving of a virtual tape to the virtual tape shelf (VTS) after the\n         archiving process is initiated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94893f93-793c-49b0-bb42-f12f93dd50ef"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieval",
      "item": [
        {
          "id": "c3bec31c-ab81-4647-b54d-b67e3b9e7190",
          "name": "cancelRetrieval",
          "request": {
            "url": "http://example.com/api/?Action=CancelRetrieval?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels retrieval of a virtual tape from the virtual tape shelf (VTS) to a gateway\n         after the retrieval process is initiated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dec372c6-8b26-4141-a03e-e248311a8da4"
            }
          ]
        }
      ]
    },
    {
      "name": "Cached SCSI Volume",
      "item": [
        {
          "id": "f801b7f6-ce80-4b3d-b685-f3515de0aa2a",
          "name": "createCachediSCSIVolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateCachediSCSIVolume?ClientToken=ClientToken&GatewayARN=GatewayARN&NetworkInterfaceId=NetworkInterfaceId&SnapshotId=SnapshotId&SourceVolumeARN=SourceVolumeARN&TargetName=TargetName&VolumeSizeInBytes=VolumeSizeInBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a cached volume on a specified cached gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42f77e47-f6bd-4cdb-90d2-6e6a52a9ecc7"
            }
          ]
        }
      ]
    },
    {
      "name": "NFS File Share",
      "item": [
        {
          "id": "2d656320-5e9b-4cab-ae9b-97abc7de5cec",
          "name": "createNFSFileShare",
          "request": {
            "url": "http://example.com/api/?Action=CreateNFSFileShare?ClientToken=ClientToken&DefaultStorageClass=DefaultStorageClass&GatewayARN=GatewayARN&KMSEncrypted=KMSEncrypted&KMSKey=KMSKey&LocationARN=LocationARN&NFSFileShareDefaults=NFSFileShareDefaults&Role=Role",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a file share on an existing file gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09ac5532-d3ac-4c29-87dc-a6a4ded23b7e"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshots",
      "item": [
        {
          "id": "55c4f2eb-75e2-4eab-8f27-b049bf650bb0",
          "name": "createSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshot?SnapshotDescription=SnapshotDescription&VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a snapshot of a volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7bcee6e-2469-4f37-aa09-1ecbfd7645c5"
            }
          ]
        },
        {
          "id": "e6273bde-d728-40cf-99ce-cb00cfda0744",
          "name": "createSnapshotFromVolumeRecoveryPoint",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshotFromVolumeRecoveryPoint?SnapshotDescription=SnapshotDescription&VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a snapshot of a gateway from a volume recovery point."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9abaa001-ede9-4677-bfde-98c8b779ec67"
            }
          ]
        },
        {
          "id": "7697fa43-673f-43e2-a435-97f15c354cd0",
          "name": "deleteSnapshotSchedule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSnapshotSchedule?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a snapshot of a volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3adcdb0d-2901-4717-be95-8091f7d9c8ea"
            }
          ]
        },
        {
          "id": "bebc40b1-5215-46c0-b492-a70f6bf3baca",
          "name": "describeSnapshotSchedule",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshotSchedule?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the snapshot schedule for the specified gateway volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "caabc736-c175-4769-b63a-aa51a965485c"
            }
          ]
        }
      ]
    },
    {
      "name": "Stored SCSI Volume",
      "item": [
        {
          "id": "c68d897a-8362-4f2b-a13b-1d3900b90bba",
          "name": "createStorediSCSIVolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateStorediSCSIVolume?DiskId=DiskId&GatewayARN=GatewayARN&NetworkInterfaceId=NetworkInterfaceId&PreserveExistingData=PreserveExistingData&SnapshotId=SnapshotId&TargetName=TargetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a volume on a specified gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "556b5130-6721-4da8-abc3-3919d048dbe7"
            }
          ]
        }
      ]
    },
    {
      "name": "Tapes",
      "item": [
        {
          "id": "9cf7013b-4cc1-460f-a002-de2169e081cb",
          "name": "createTapes",
          "request": {
            "url": "http://example.com/api/?Action=CreateTapes?ClientToken=ClientToken&GatewayARN=GatewayARN&NumTapesToCreate=NumTapesToCreate&TapeBarcodePrefix=TapeBarcodePrefix&TapeSizeInBytes=TapeSizeInBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates one or more virtual tapes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c809b2ca-5ae1-408e-b39b-747a14c552d5"
            }
          ]
        },
        {
          "id": "91b96179-23fd-4a76-9cb9-44cd67222049",
          "name": "deleteTape",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTape?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified virtual tape."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "044ebb60-e7e3-48e7-8e45-faf0fabb4368"
            }
          ]
        },
        {
          "id": "088ceaab-1745-4421-bcff-938757dcb8ac",
          "name": "deleteTapeArchive",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTapeArchive?TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified virtual tape from the virtual tape shelf (VTS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41f8c42a-e4a2-429d-8293-bf7c240d2df9"
            }
          ]
        },
        {
          "id": "083c448d-f4dc-4f4e-b042-6ffbd5044372",
          "name": "describeTapes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTapes?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker&TapeARNs=TapeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the specified Amazon Resource Name (ARN) of virtual tapes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "00168ea5-32ed-4116-a2ba-e0cbaf32575a"
            }
          ]
        },
        {
          "id": "4366ed59-d17f-409d-8a9b-f98457fb493d",
          "name": "listTapes",
          "request": {
            "url": "http://example.com/api/?Action=ListTapes?Limit=Limit&Marker=Marker&TapeARNs=TapeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists virtual tapes in your virtual tape library (VTL) and your virtual tape shelf\n         (VTS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c29f48e-30ba-4d41-bdb2-4a428b94f053"
            }
          ]
        },
        {
          "id": "3c7e6388-0e93-41cc-8f49-d64f39d32a41",
          "name": "retrieveTapeArchive",
          "request": {
            "url": "http://example.com/api/?Action=RetrieveTapeArchive?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves an archived virtual tape from the virtual tape shelf (VTS) to a\n         gateway-VTL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19e611bc-14c0-4acf-9d45-d0efc97e01b8"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape With Barcode",
      "item": [
        {
          "id": "8835dd82-e5ca-4e4a-b8a5-0cfaf48ec970",
          "name": "createTapeWithBarcode",
          "request": {
            "url": "http://example.com/api/?Action=CreateTapeWithBarcode?GatewayARN=GatewayARN&TapeBarcode=TapeBarcode&TapeSizeInBytes=TapeSizeInBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a virtual tape by using your own barcode."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d7bc731-4d2c-4dd9-9adc-71003aae87bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Bandwidth Rate Limit",
      "item": [
        {
          "id": "0249b24d-d10d-42b6-9159-5db2f9ec3643",
          "name": "deleteBandwidthRateLimit",
          "request": {
            "url": "http://example.com/api/?Action=DeleteBandwidthRateLimit?BandwidthType=BandwidthType&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the bandwidth rate limits of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "591779a6-39dd-4b24-86a7-ca7f81dbcf96"
            }
          ]
        },
        {
          "id": "ed9a91f2-ecf7-473e-9c42-269727158997",
          "name": "describeBandwidthRateLimit",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBandwidthRateLimit?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the bandwidth rate limits of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef7aef1f-e819-4c6e-a0f5-2f82cfb28849"
            }
          ]
        },
        {
          "id": "5fa71132-3ab9-4b7a-87a5-60e827dd20d4",
          "name": "updateBandwidthRateLimit",
          "request": {
            "url": "http://example.com/api/?Action=UpdateBandwidthRateLimit?AverageDownloadRateLimitInBitsPerSec=AverageDownloadRateLimitInBitsPerSec&AverageUploadRateLimitInBitsPerSec=AverageUploadRateLimitInBitsPerSec&GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the bandwidth rate limits of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f9d3a39-32c5-4329-99dc-542209347cb7"
            }
          ]
        }
      ]
    },
    {
      "name": "Chap Credentials",
      "item": [
        {
          "id": "bfc1a020-23fa-4db6-8ffa-6043d99e6f19",
          "name": "deleteChapCredentials",
          "request": {
            "url": "http://example.com/api/?Action=DeleteChapCredentials?InitiatorName=InitiatorName&TargetARN=TargetARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes Challenge-Handshake Authentication Protocol (CHAP) credentials for a\n         specified iSCSI target and initiator pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65741945-dc9d-47f6-88ee-481aaf055f6f"
            }
          ]
        },
        {
          "id": "88df7ad4-aa49-46ed-97b0-2f6b4a6eb27a",
          "name": "describeChapCredentials",
          "request": {
            "url": "http://example.com/api/?Action=DescribeChapCredentials?TargetARN=TargetARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an array of Challenge-Handshake Authentication Protocol (CHAP) credentials\n         information for a specified iSCSI target, one for each target-initiator pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfe65256-589e-414c-a683-22e77614f418"
            }
          ]
        }
      ]
    },
    {
      "name": "File Share",
      "item": [
        {
          "id": "da991e25-9ae7-4f63-b7ae-fc8ef1bf0e70",
          "name": "deleteFileShare",
          "request": {
            "url": "http://example.com/api/?Action=DeleteFileShare?FileShareARN=FileShareARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a file share from a file gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74661fc5-55f9-44b8-9689-70c1b2cea450"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "9631a39b-6b8f-466d-9d69-e156c003ce0f",
          "name": "deleteVolume",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVolume?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified gateway volume that you previously created using the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2be2b46-7076-4d12-81ea-f7fe88fe7769"
            }
          ]
        },
        {
          "id": "146c506d-d055-4946-b021-1eb8b9c3f195",
          "name": "listVolumes",
          "request": {
            "url": "http://example.com/api/?Action=ListVolumes?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the iSCSI stored volumes of a gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d3e912e-915c-462c-81b5-ea0a201dac57"
            }
          ]
        }
      ]
    },
    {
      "name": "Cached SCSI Volumes",
      "item": [
        {
          "id": "ffc16d51-4122-4f77-ad7c-95920c281d4d",
          "name": "describeCachediSCSIVolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCachediSCSIVolumes?VolumeARNs=VolumeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the gateway volumes specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebe8dcdc-9968-415b-a01e-ccc5c2a2ddaa"
            }
          ]
        }
      ]
    },
    {
      "name": "Maintenance",
      "item": [
        {
          "id": "04eb3c3b-77f1-4d85-ae04-01d404f33aa9",
          "name": "describeMaintenanceStartTime",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMaintenanceStartTime?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns your gateway's weekly maintenance start time including the day and time of\n         the week."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b9a2754-660a-411d-b5ea-1dbe5b662c82"
            }
          ]
        }
      ]
    },
    {
      "name": "NFS File Shares",
      "item": [
        {
          "id": "2ef15a77-3b65-4dc9-819c-ab91fc021479",
          "name": "describeNFSFileShares",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNFSFileShares?FileShareARNList=FileShareARNList",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a description for one or more file shares from a file gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57fef8bb-3f79-4fc7-a593-df6d1e5be5b4"
            }
          ]
        }
      ]
    },
    {
      "name": "Stored SCSI Volumes",
      "item": [
        {
          "id": "d2b7414c-3615-45d0-81c5-7a07ba9dbe44",
          "name": "describeStorediSCSIVolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStorediSCSIVolumes?VolumeARNs=VolumeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the description of the gateway volumes specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6d5c9ff-9761-488c-a473-b88bb5530c42"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape Archives",
      "item": [
        {
          "id": "2151b6b5-8809-468f-a1ed-1d38f8071306",
          "name": "describeTapeArchives",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTapeArchives?Limit=Limit&Marker=Marker&TapeARNs=TapeARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of specified virtual tapes in the virtual tape shelf\n         (VTS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8e9d2ea-88bc-4e02-9b6c-e29758c3250e"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape Recovery Points",
      "item": [
        {
          "id": "b2c42e2a-db3c-4d07-9489-7abd371da359",
          "name": "describeTapeRecoveryPoints",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTapeRecoveryPoints?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of virtual tape recovery points that are available for the specified\n         gateway-VTL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb3d81d9-48f9-4dff-8efc-b10488d6d0c8"
            }
          ]
        }
      ]
    },
    {
      "name": "VTL Devices",
      "item": [
        {
          "id": "ce2ee7f7-cd77-4ef3-b93b-486d6be6c989",
          "name": "describeVTLDevices",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVTLDevices?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker&VTLDeviceARNs=VTLDeviceARNs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of virtual tape library (VTL) devices for the specified\n         gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5280a4a-cae7-4eac-b377-9c986957320a"
            }
          ]
        }
      ]
    },
    {
      "name": "File Shares",
      "item": [
        {
          "id": "26ce4257-a736-4675-83b7-3761c3997870",
          "name": "listFileShares",
          "request": {
            "url": "http://example.com/api/?Action=ListFileShares?GatewayARN=GatewayARN&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of the file shares for a specific file gateway, or the list of file shares that belong to the calling user account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb8dbad1-08bf-4f96-8be8-191d7588cd5e"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateways",
      "item": [
        {
          "id": "92f37c2d-a15e-4671-b9e5-80b089560835",
          "name": "listGateways",
          "request": {
            "url": "http://example.com/api/?Action=ListGateways?Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists gateways owned by an AWS account in a region specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f901e03e-77ba-423b-be6f-c3b4d71730be"
            }
          ]
        }
      ]
    },
    {
      "name": "Local Disks",
      "item": [
        {
          "id": "bb349fdb-b7e7-4a3d-a1dd-f289170541aa",
          "name": "listLocalDisks",
          "request": {
            "url": "http://example.com/api/?Action=ListLocalDisks?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of the gateway's local disks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "950ff446-a7b7-4243-8e6a-86ecd6ec4435"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Initiators",
      "item": [
        {
          "id": "a5137935-1ab4-409e-a17b-7334b6f63514",
          "name": "listVolumeInitiators",
          "request": {
            "url": "http://example.com/api/?Action=ListVolumeInitiators?VolumeARN=VolumeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists iSCSI initiators that are connected to a volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e68b5850-ee50-449a-8948-aab2e029941e"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Recovery",
      "item": [
        {
          "id": "8860bbbd-26ff-41a7-884b-c6c01e7dd9c9",
          "name": "listVolumeRecoveryPoints",
          "request": {
            "url": "http://example.com/api/?Action=ListVolumeRecoveryPoints?GatewayARN=GatewayARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the recovery points for a specified gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8558d274-4fbe-4815-a115-5a5793ae8933"
            }
          ]
        }
      ]
    },
    {
      "name": "Tape Recovery",
      "item": [
        {
          "id": "826f205d-c816-448e-97a4-f9c6e16b9fec",
          "name": "retrieveTapeRecoveryPoint",
          "request": {
            "url": "http://example.com/api/?Action=RetrieveTapeRecoveryPoint?GatewayARN=GatewayARN&TapeARN=TapeARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the recovery point for the specified virtual tape."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38ef222a-711a-49da-a43c-e40e58a2a1ef"
            }
          ]
        }
      ]
    },
    {
      "name": "Local Console Password",
      "item": [
        {
          "id": "d9c6086b-d05a-4772-b270-5f3783345ec1",
          "name": "setLocalConsolePassword",
          "request": {
            "url": "http://example.com/api/?Action=SetLocalConsolePassword?GatewayARN=GatewayARN&LocalConsolePassword=LocalConsolePassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the password for your VM local console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ba50706-72d7-4fc5-8c1c-b7603254a5d1"
            }
          ]
        }
      ]
    }
  ]
}