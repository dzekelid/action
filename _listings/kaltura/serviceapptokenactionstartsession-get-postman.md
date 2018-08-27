{
  "info": {
    "name": "Kaltura VPaaS Get Service Apptoken Action Startsession",
    "_postman_id": "52cca9d4-cc56-4035-89ee-d3d73eef572d",
    "description": "Starts a new KS (kaltura Session) based on application authentication token id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "451a99ce-cc4d-4ba8-8a35-46872821e1fe",
          "name": "accessControl.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/add?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Access Control Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f7e547a-f8ee-4ad0-83ae-2f9a8033227d"
            }
          ]
        },
        {
          "id": "3705e59a-85d7-44cf-a52c-d9f9835993c7",
          "name": "accessControl.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c66aafb-98b5-449b-bf6d-d8e8626ae14a"
            }
          ]
        },
        {
          "id": "ddcba24b-617e-41bf-b440-e92220b62f07",
          "name": "accessControl.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efdbd7c3-917a-4cd6-9b83-1a161c16ff18"
            }
          ]
        },
        {
          "id": "6fc6e0fa-0a07-4df9-911e-35be9d941071",
          "name": "accessControl.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Access Control Profiles by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9feadce8-1af9-451d-85b0-5d9fa1eb8139"
            }
          ]
        },
        {
          "id": "fdceb8a8-bcde-4839-b7dd-1267993c94a0",
          "name": "accessControl.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/update?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06b440e5-b9fc-4335-b74d-caf734f89209"
            }
          ]
        },
        {
          "id": "4a866b2d-1973-4a01-ae38-103cd411a5e9",
          "name": "accessControlProfile.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/add?accessControlProfile[description]=%7B%7D&accessControlProfile[isDefault]=%7B%7D&accessControlProfile[name]=%7B%7D&accessControlProfile[rules]=%7B%7D&accessControlProfile[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new access control profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be54503d-6402-488e-868b-cbc460b80333"
            }
          ]
        },
        {
          "id": "ec5397b6-da8e-43f7-a806-cca9b2cc0ff2",
          "name": "accessControlProfile.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ae0f9be-3e03-47ab-9627-b550f985512b"
            }
          ]
        },
        {
          "id": "f15652d9-2d34-48d8-b319-f56e0a8125ad",
          "name": "accessControlProfile.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69e11a98-f6cb-4d4a-91df-17698376822c"
            }
          ]
        },
        {
          "id": "bce1a6a4-b939-4f34-b018-7fac39edb740",
          "name": "accessControlProfile.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List access control profiles by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afc6dc0c-346f-4212-a999-ac36dad63a3a"
            }
          ]
        },
        {
          "id": "f35ac894-a820-4208-a24b-ac1ce7c82cb2",
          "name": "accessControlProfile.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/update?accessControlProfile[description]=%7B%7D&accessControlProfile[isDefault]=%7B%7D&accessControlProfile[name]=%7B%7D&accessControlProfile[rules]=%7B%7D&accessControlProfile[systemName]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd62677d-3866-4987-aec9-97e5e6e90518"
            }
          ]
        },
        {
          "id": "8002ceaf-e3b3-4d25-9b70-16145c1dca95",
          "name": "adminUser.login",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/login?email=%7B%7D&No Name=%7B%7D&partnerId=%7B%7D&password=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an admin session using admin email and password (Used for login to the KMC application)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da10186c-c219-4182-a13c-fc538aa51deb"
            }
          ]
        },
        {
          "id": "36d90fd1-8f6d-4952-bc8a-61e54a1636e3",
          "name": "adminUser.resetPassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/resetPassword?email=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Reset admin user password and send it to the users email address"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d377af1-98cd-45d1-ad05-026d77bc283b"
            }
          ]
        },
        {
          "id": "ef466d02-85e5-4271-a120-fb26da43bb23",
          "name": "adminUser.setInitialPassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/setInitialPassword?hashKey=%7B%7D&newPassword=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set initial users password"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f9536bf-6246-47a3-a946-3a699820362b"
            }
          ]
        },
        {
          "id": "91d13e39-ce46-41a8-bbb6-cd74d25b3f75",
          "name": "adminUser.updatePassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/updatePassword?email=%7B%7D&newEmail=%7B%7D&newPassword=%7B%7D&No Name=%7B%7D&password=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update admin user password and email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86563efb-71af-4358-9ff4-9cd712b7d2f6"
            }
          ]
        },
        {
          "id": "9044e72a-b12c-4b5a-a2e9-e04fc70cb991",
          "name": "analytics.query",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/analytics/action/query?filter[dimensions]=%7B%7D&filter[filters]=%7B%7D&filter[from_time]=%7B%7D&filter[metrics]=%7B%7D&filter[orderBy]=%7B%7D&filter[to_time]=%7B%7D&filter[utcOffset]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "report query action allows to get a analytics data for specific query dimensions, metrics and filters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96f4b48c-06bc-407b-8898-29cd77b64548"
            }
          ]
        },
        {
          "id": "5c9ca842-fc92-4ba0-8d28-4731f46a1784",
          "name": "annotation.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/add?annotation[adType]=%7B%7D&annotation[answerKey]=%7B%7D&annotation[assetId]=%7B%7D&annotation[code]=%7B%7D&annotation[correctAnswerKeys]=%7B%7D&annotation[description]=%7B%7D&annotation[duration]=%7B%7D&annotation[endTime]=%7B%7D&annotation[entryId]=%7B%7D&annotation[eventType]=%7B%7D&annotation[explanation]=%7B%7D&annotation[forceStop]=%7B%7D&annotation[hint]=%7B%7D&annotation[isPublic]=%7B%7D&annotation[objectType]=%7B%7D&annotation[optionalAnswers]=%7B%7D&annotation[parentId]=%7B%7D&annotation[partnerData]=%7B%7D&annotation[partnerSortValue]=%7B%7D&annotation[protocolType]=%7B%7D&annotation[question]=%7B%7D&annotation[quizUserEntryId]=%7B%7D&annotation[searchableOnEntry]=%7B%7D&annotation[sourceUrl]=%7B%7D&annotation[startTime]=%7B%7D&annotation[subType]=%7B%7D&annotation[systemName]=%7B%7D&annotation[tags]=%7B%7D&annotation[text]=%7B%7D&annotation[thumbOffset]=%7B%7D&annotation[title]=%7B%7D&annotation[triggeredAt]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to add an annotation object associated with an entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76147203-8377-4e43-91fc-b6d082ff8171"
            }
          ]
        },
        {
          "id": "fa470796-2774-4598-97cc-772bf609936e",
          "name": "annotation.addFromBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/addFromBulk?No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "fileData",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Allows you to add multiple cue points objects by uploading XML that contains multiple cue point definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f412700e-affe-42db-b91c-2fedeafa17ff"
            }
          ]
        },
        {
          "id": "a8af64eb-fb9d-4441-8709-ff8d768d4399",
          "name": "annotation.clone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/clone?entryId=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Clone cuePoint with id to given entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f38d13f-5f29-4c61-898c-6dc71c3e7949"
            }
          ]
        },
        {
          "id": "51173183-1bc3-4bea-b6a0-91d13eaea7ff",
          "name": "annotation.count",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/count?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "count cue point objects by filter"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ad9bf1b-0da3-4c14-9b57-058398a6ee49"
            }
          ]
        },
        {
          "id": "1f379203-8e08-4c81-9148-0964f1affbfc",
          "name": "annotation.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "delete cue point by id, and delete all children cue points"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da0ef52a-8972-40c8-8c4a-18bc2c1b5c98"
            }
          ]
        },
        {
          "id": "49ba6f3f-e66b-4b69-a3c2-db1136ef7b9f",
          "name": "annotation.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an CuePoint object by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e2c6fe8-f85e-47da-9616-ae7cc0d2bd4f"
            }
          ]
        },
        {
          "id": "eb772cfc-a303-4494-bae7-37629ee3ab37",
          "name": "annotation.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List annotation objects by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a7cc56f-b00f-402d-8405-63f6c359bb29"
            }
          ]
        },
        {
          "id": "33e0baf4-e622-45cc-8a2f-1db4f6ce6cae",
          "name": "annotation.serveBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/serveBulk?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download multiple cue points objects as XML definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81a812c2-9e72-44f9-8bb0-b8e06351e745"
            }
          ]
        },
        {
          "id": "0cffa6b4-885f-45fd-9f1a-15233d720676",
          "name": "annotation.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/update?annotation[adType]=%7B%7D&annotation[answerKey]=%7B%7D&annotation[assetId]=%7B%7D&annotation[code]=%7B%7D&annotation[correctAnswerKeys]=%7B%7D&annotation[description]=%7B%7D&annotation[duration]=%7B%7D&annotation[endTime]=%7B%7D&annotation[entryId]=%7B%7D&annotation[eventType]=%7B%7D&annotation[explanation]=%7B%7D&annotation[forceStop]=%7B%7D&annotation[hint]=%7B%7D&annotation[isPublic]=%7B%7D&annotation[objectType]=%7B%7D&annotation[optionalAnswers]=%7B%7D&annotation[parentId]=%7B%7D&annotation[partnerData]=%7B%7D&annotation[partnerSortValue]=%7B%7D&annotation[protocolType]=%7B%7D&annotation[question]=%7B%7D&annotation[quizUserEntryId]=%7B%7D&annotation[searchableOnEntry]=%7B%7D&annotation[sourceUrl]=%7B%7D&annotation[startTime]=%7B%7D&annotation[subType]=%7B%7D&annotation[systemName]=%7B%7D&annotation[tags]=%7B%7D&annotation[text]=%7B%7D&annotation[thumbOffset]=%7B%7D&annotation[title]=%7B%7D&annotation[triggeredAt]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update annotation by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d7cde79-8830-4f4d-beba-10df9a1c3049"
            }
          ]
        },
        {
          "id": "63de1d1f-e79a-4aee-8255-0ca28425c316",
          "name": "annotation.updateStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/updateStatus?id=%7B%7D&No Name=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update cuePoint status by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e012e550-0c89-4ab9-ad30-90c3b9e69946"
            }
          ]
        },
        {
          "id": "96a9e0c9-47be-4c48-9cb9-0309b3db4e90",
          "name": "appToken.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/add?appToken[expiry]=%7B%7D&appToken[hashType]=%7B%7D&appToken[sessionDuration]=%7B%7D&appToken[sessionPrivileges]=%7B%7D&appToken[sessionType]=%7B%7D&appToken[sessionUserId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new application authentication token"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4abf8bb7-b983-4dee-9ebf-7216c3e7cef0"
            }
          ]
        },
        {
          "id": "1a3a637d-6d7d-4f28-9eef-840bf59065f4",
          "name": "appToken.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b620ff91-bc0f-4f1a-85a5-f7c75a4060db"
            }
          ]
        },
        {
          "id": "cee5657e-115d-4d4a-9d09-90851b07eaba",
          "name": "appToken.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ff25469-841b-4ab1-bd73-47e0648ce225"
            }
          ]
        },
        {
          "id": "79b55b81-c298-44d3-ab1a-53d560a52025",
          "name": "appToken.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List application authentication tokens by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f209c3d-2b57-44f8-8d62-57e5e81dd6d3"
            }
          ]
        },
        {
          "id": "b6ce9ef7-6f82-4021-bb6b-2b9f5dcf5379",
          "name": "appToken.startSession",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/startSession?expiry=%7B%7D&id=%7B%7D&No Name=%7B%7D&tokenHash=%7B%7D&type=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a new KS (kaltura Session) based on application authentication token id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ea58a71-7578-4527-8069-42b21856c206"
            }
          ]
        }
      ]
    }
  ]
}