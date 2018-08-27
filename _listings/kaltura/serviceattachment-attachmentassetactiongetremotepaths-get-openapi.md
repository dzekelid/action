---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Attachment Attachmentasset Action Getremotepaths
  description: Get remote storage existing paths for the asset
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/accesscontrol/action/add:
    get:
      summary: Get Service Access Control Action Add
      description: Add new Access Control Profile
      operationId: accessControl.add
      x-api-path-slug: serviceaccesscontrolactionadd-get
      parameters:
      - in: query
        name: accessControl[description]
        description: The description of the Access Control Profile
      - in: query
        name: accessControl[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`True if this Conversion Profile
          is the default'
      - in: query
        name: accessControl[name]
        description: The name of the Access Control Profile
      - in: query
        name: accessControl[restrictions]
      - in: query
        name: accessControl[systemName]
        description: System name of the Access Control Profile
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrol
      - Action
      - Add
  /service/accesscontrol/action/delete:
    get:
      summary: Get Service Access Control Action Delete
      description: Delete Access Control Profile by id
      operationId: accessControl.delete
      x-api-path-slug: serviceaccesscontrolactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrol
      - Action
      - Delete
  /service/accesscontrol/action/get:
    get:
      summary: Get Service Access Control Action Get
      description: Get Access Control Profile by id
      operationId: accessControl.get
      x-api-path-slug: serviceaccesscontrolactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrol
      - Action
      - Get
  /service/accesscontrol/action/list:
    get:
      summary: Get Service Access Control Action List
      description: List Access Control Profiles by filter and pager
      operationId: accessControl.list
      x-api-path-slug: serviceaccesscontrolactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrol
      - Action
      - List
  /service/accesscontrol/action/update:
    get:
      summary: Get Service Access Control Action Update
      description: Update Access Control Profile by id
      operationId: accessControl.update
      x-api-path-slug: serviceaccesscontrolactionupdate-get
      parameters:
      - in: query
        name: accessControl[description]
        description: The description of the Access Control Profile
      - in: query
        name: accessControl[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`True if this Conversion Profile
          is the default'
      - in: query
        name: accessControl[name]
        description: The name of the Access Control Profile
      - in: query
        name: accessControl[restrictions]
      - in: query
        name: accessControl[systemName]
        description: System name of the Access Control Profile
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrol
      - Action
      - Update
  /service/accesscontrolprofile/action/add:
    get:
      summary: Get Service Access Controlprofile Action Add
      description: Add new access control profile
      operationId: accessControlProfile.add
      x-api-path-slug: serviceaccesscontrolprofileactionadd-get
      parameters:
      - in: query
        name: accessControlProfile[description]
        description: The description of the Access Control Profile
      - in: query
        name: accessControlProfile[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`True if this access control
          profile is the partner default'
      - in: query
        name: accessControlProfile[name]
        description: The name of the Access Control Profile
      - in: query
        name: accessControlProfile[rules]
      - in: query
        name: accessControlProfile[systemName]
        description: System name of the Access Control Profile
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrolprofile
      - Action
      - Add
  /service/accesscontrolprofile/action/delete:
    get:
      summary: Get Service Access Controlprofile Action Delete
      description: Delete access control profile by id
      operationId: accessControlProfile.delete
      x-api-path-slug: serviceaccesscontrolprofileactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrolprofile
      - Action
      - Delete
  /service/accesscontrolprofile/action/get:
    get:
      summary: Get Service Access Controlprofile Action Get
      description: Get access control profile by id
      operationId: accessControlProfile.get
      x-api-path-slug: serviceaccesscontrolprofileactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrolprofile
      - Action
      - Get
  /service/accesscontrolprofile/action/list:
    get:
      summary: Get Service Access Controlprofile Action List
      description: List access control profiles by filter and pager
      operationId: accessControlProfile.list
      x-api-path-slug: serviceaccesscontrolprofileactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrolprofile
      - Action
      - List
  /service/accesscontrolprofile/action/update:
    get:
      summary: Get Service Access Controlprofile Action Update
      description: Update access control profile by id
      operationId: accessControlProfile.update
      x-api-path-slug: serviceaccesscontrolprofileactionupdate-get
      parameters:
      - in: query
        name: accessControlProfile[description]
        description: The description of the Access Control Profile
      - in: query
        name: accessControlProfile[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`True if this access control
          profile is the partner default'
      - in: query
        name: accessControlProfile[name]
        description: The name of the Access Control Profile
      - in: query
        name: accessControlProfile[rules]
      - in: query
        name: accessControlProfile[systemName]
        description: System name of the Access Control Profile
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Accesscontrolprofile
      - Action
      - Update
  /service/adminuser/action/login:
    get:
      summary: Get Service Adminuser Action Login
      description: Get an admin session using admin email and password (Used for login
        to the KMC application)
      operationId: adminUser.login
      x-api-path-slug: serviceadminuseractionlogin-get
      parameters:
      - in: query
        name: email
      - in: query
        name: No Name
      - in: query
        name: partnerId
      - in: query
        name: password
      responses:
        200:
          description: OK
      tags:
      - Service
      - Adminuser
      - Action
      - Login
  /service/adminuser/action/resetPassword:
    get:
      summary: Get Service Adminuser Action Resetpassword
      description: Reset admin user password and send it to the users email address
      operationId: adminUser.resetPassword
      x-api-path-slug: serviceadminuseractionresetpassword-get
      parameters:
      - in: query
        name: email
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Adminuser
      - Action
      - ResetPassword
  /service/adminuser/action/setInitialPassword:
    get:
      summary: Get Service Adminuser Action Setinitialpassword
      description: Set initial users password
      operationId: adminUser.setInitialPassword
      x-api-path-slug: serviceadminuseractionsetinitialpassword-get
      parameters:
      - in: query
        name: hashKey
      - in: query
        name: newPassword
        description: new password to set
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Adminuser
      - Action
      - SetInitialPassword
  /service/adminuser/action/updatePassword:
    get:
      summary: Get Service Adminuser Action Updatepassword
      description: Update admin user password and email
      operationId: adminUser.updatePassword
      x-api-path-slug: serviceadminuseractionupdatepassword-get
      parameters:
      - in: query
        name: email
      - in: query
        name: newEmail
        description: Optional, provide only when you want to update the email
      - in: query
        name: newPassword
      - in: query
        name: No Name
      - in: query
        name: password
      responses:
        200:
          description: OK
      tags:
      - Service
      - Adminuser
      - Action
      - UpdatePassword
  /service/analytics/action/query:
    get:
      summary: Get Service Analytics Action Query
      description: report query action allows to get a analytics data for specific
        query dimensions, metrics and filters.
      operationId: analytics.query
      x-api-path-slug: serviceanalyticsactionquery-get
      parameters:
      - in: query
        name: filter[dimensions]
        description: Comma separated dimensions list
      - in: query
        name: filter[filters]
      - in: query
        name: filter[from_time]
        description: Query start time (in local time) MM/dd/yyyy HH:mi
      - in: query
        name: filter[metrics]
        description: Comma separated metrics list
      - in: query
        name: filter[orderBy]
        description: Query order by metric/dimension
      - in: query
        name: filter[to_time]
        description: Query end time (in local time) MM/dd/yyyy HH:mi
      - in: query
        name: filter[utcOffset]
        description: Timezone offset from UTC (in minutes)
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Analytics
      - Action
      - Query
  /service/annotation_annotation/action/add:
    get:
      summary: Get Service Annotation Annotation Action Add
      description: Allows you to add an annotation object associated with an entry
      operationId: annotation.add
      x-api-path-slug: serviceannotation-annotationactionadd-get
      parameters:
      - in: query
        name: annotation[adType]
        description: 'Enum Type: `KalturaAdType`'
      - in: query
        name: annotation[answerKey]
      - in: query
        name: annotation[assetId]
      - in: query
        name: annotation[code]
      - in: query
        name: annotation[correctAnswerKeys]
      - in: query
        name: annotation[description]
      - in: query
        name: annotation[duration]
        description: Duration in milliseconds
      - in: query
        name: annotation[endTime]
        description: End time in milliseconds
      - in: query
        name: annotation[entryId]
        description: '`insertOnly`'
      - in: query
        name: annotation[eventType]
        description: 'Enum Type: `KalturaEventType`'
      - in: query
        name: annotation[explanation]
      - in: query
        name: annotation[forceStop]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: annotation[hint]
      - in: query
        name: annotation[isPublic]
        description: 'Enum Type: `KalturaNullableBoolean`Is the annotation public'
      - in: query
        name: annotation[objectType]
      - in: query
        name: annotation[optionalAnswers]
      - in: query
        name: annotation[parentId]
        description: '`insertOnly`'
      - in: query
        name: annotation[partnerData]
      - in: query
        name: annotation[partnerSortValue]
      - in: query
        name: annotation[protocolType]
        description: '`insertOnly`Enum Type: `KalturaAdProtocolType`'
      - in: query
        name: annotation[question]
      - in: query
        name: annotation[quizUserEntryId]
        description: '`insertOnly`'
      - in: query
        name: annotation[searchableOnEntry]
        description: 'Enum Type: `KalturaNullableBoolean`Should the cue point get
          indexed on the entry'
      - in: query
        name: annotation[sourceUrl]
      - in: query
        name: annotation[startTime]
        description: Start time in milliseconds
      - in: query
        name: annotation[subType]
        description: 'Enum Type: `KalturaThumbCuePointSubType`The sub type of the
          ThumbCuePoint'
      - in: query
        name: annotation[systemName]
      - in: query
        name: annotation[tags]
      - in: query
        name: annotation[text]
      - in: query
        name: annotation[thumbOffset]
      - in: query
        name: annotation[title]
      - in: query
        name: annotation[triggeredAt]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Add
  /service/annotation_annotation/action/addFromBulk:
    post:
      summary: Post Service Annotation Annotation Action Addfrombulk
      description: Allows you to add multiple cue points objects by uploading XML
        that contains multiple cue point definitions
      operationId: annotation.addFromBulk
      x-api-path-slug: serviceannotation-annotationactionaddfrombulk-post
      parameters:
      - in: formData
        name: fileData
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - AddFromBulk
  /service/annotation_annotation/action/clone:
    get:
      summary: Get Service Annotation Annotation Action Clone
      description: Clone cuePoint with id to given entry
      operationId: annotation.clone
      x-api-path-slug: serviceannotation-annotationactionclone-get
      parameters:
      - in: query
        name: entryId
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Clone
  /service/annotation_annotation/action/count:
    get:
      summary: Get Service Annotation Annotation Action Count
      description: count cue point objects by filter
      operationId: annotation.count
      x-api-path-slug: serviceannotation-annotationactioncount-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[codeEqual]
      - in: query
        name: filter[codeIn]
      - in: query
        name: filter[codeLike]
      - in: query
        name: filter[codeMultiLikeAnd]
      - in: query
        name: filter[codeMultiLikeOr]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[cuePointTypeEqual]
        description: 'Enum Type: `KalturaCuePointType`'
      - in: query
        name: filter[cuePointTypeIn]
      - in: query
        name: filter[descriptionLike]
      - in: query
        name: filter[descriptionMultiLikeAnd]
      - in: query
        name: filter[descriptionMultiLikeOr]
      - in: query
        name: filter[durationGreaterThanOrEqual]
      - in: query
        name: filter[durationLessThanOrEqual]
      - in: query
        name: filter[endTimeGreaterThanOrEqual]
      - in: query
        name: filter[endTimeLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[eventTypeEqual]
        description: 'Enum Type: `KalturaEventType`'
      - in: query
        name: filter[eventTypeIn]
      - in: query
        name: filter[forceStopEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[isPublicEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentIdEqual]
      - in: query
        name: filter[parentIdIn]
      - in: query
        name: filter[partnerSortValueEqual]
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueIn]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[protocolTypeEqual]
        description: 'Enum Type: `KalturaAdProtocolType`'
      - in: query
        name: filter[protocolTypeIn]
      - in: query
        name: filter[questionLike]
      - in: query
        name: filter[questionMultiLikeAnd]
      - in: query
        name: filter[questionMultiLikeOr]
      - in: query
        name: filter[quizUserEntryIdEqual]
      - in: query
        name: filter[quizUserEntryIdIn]
      - in: query
        name: filter[startTimeGreaterThanOrEqual]
      - in: query
        name: filter[startTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCuePointStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[subTypeEqual]
        description: 'Enum Type: `KalturaThumbCuePointSubType`'
      - in: query
        name: filter[subTypeIn]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: filter[tagsLike]
      - in: query
        name: filter[tagsMultiLikeAnd]
      - in: query
        name: filter[tagsMultiLikeOr]
      - in: query
        name: filter[textLike]
      - in: query
        name: filter[textMultiLikeAnd]
      - in: query
        name: filter[textMultiLikeOr]
      - in: query
        name: filter[titleLike]
      - in: query
        name: filter[titleMultiLikeAnd]
      - in: query
        name: filter[titleMultiLikeOr]
      - in: query
        name: filter[triggeredAtGreaterThanOrEqual]
      - in: query
        name: filter[triggeredAtLessThanOrEqual]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[userIdCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqualCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqual]
      - in: query
        name: filter[userIdIn]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Count
  /service/annotation_annotation/action/delete:
    get:
      summary: Get Service Annotation Annotation Action Delete
      description: delete cue point by id, and delete all children cue points
      operationId: annotation.delete
      x-api-path-slug: serviceannotation-annotationactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Delete
  /service/annotation_annotation/action/get:
    get:
      summary: Get Service Annotation Annotation Action Get
      description: Retrieve an CuePoint object by id
      operationId: annotation.get
      x-api-path-slug: serviceannotation-annotationactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Get
  /service/annotation_annotation/action/list:
    get:
      summary: Get Service Annotation Annotation Action List
      description: List annotation objects by filter and pager
      operationId: annotation.list
      x-api-path-slug: serviceannotation-annotationactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[codeEqual]
      - in: query
        name: filter[codeIn]
      - in: query
        name: filter[codeLike]
      - in: query
        name: filter[codeMultiLikeAnd]
      - in: query
        name: filter[codeMultiLikeOr]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[cuePointTypeEqual]
        description: 'Enum Type: `KalturaCuePointType`'
      - in: query
        name: filter[cuePointTypeIn]
      - in: query
        name: filter[descriptionLike]
      - in: query
        name: filter[descriptionMultiLikeAnd]
      - in: query
        name: filter[descriptionMultiLikeOr]
      - in: query
        name: filter[durationGreaterThanOrEqual]
      - in: query
        name: filter[durationLessThanOrEqual]
      - in: query
        name: filter[endTimeGreaterThanOrEqual]
      - in: query
        name: filter[endTimeLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[eventTypeEqual]
        description: 'Enum Type: `KalturaEventType`'
      - in: query
        name: filter[eventTypeIn]
      - in: query
        name: filter[forceStopEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[isPublicEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentIdEqual]
      - in: query
        name: filter[parentIdIn]
      - in: query
        name: filter[partnerSortValueEqual]
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueIn]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[protocolTypeEqual]
        description: 'Enum Type: `KalturaAdProtocolType`'
      - in: query
        name: filter[protocolTypeIn]
      - in: query
        name: filter[questionLike]
      - in: query
        name: filter[questionMultiLikeAnd]
      - in: query
        name: filter[questionMultiLikeOr]
      - in: query
        name: filter[quizUserEntryIdEqual]
      - in: query
        name: filter[quizUserEntryIdIn]
      - in: query
        name: filter[startTimeGreaterThanOrEqual]
      - in: query
        name: filter[startTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCuePointStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[subTypeEqual]
        description: 'Enum Type: `KalturaThumbCuePointSubType`'
      - in: query
        name: filter[subTypeIn]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: filter[tagsLike]
      - in: query
        name: filter[tagsMultiLikeAnd]
      - in: query
        name: filter[tagsMultiLikeOr]
      - in: query
        name: filter[textLike]
      - in: query
        name: filter[textMultiLikeAnd]
      - in: query
        name: filter[textMultiLikeOr]
      - in: query
        name: filter[titleLike]
      - in: query
        name: filter[titleMultiLikeAnd]
      - in: query
        name: filter[titleMultiLikeOr]
      - in: query
        name: filter[triggeredAtGreaterThanOrEqual]
      - in: query
        name: filter[triggeredAtLessThanOrEqual]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[userIdCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqualCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqual]
      - in: query
        name: filter[userIdIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - List
  /service/annotation_annotation/action/serveBulk:
    get:
      summary: Get Service Annotation Annotation Action Servebulk
      description: Download multiple cue points objects as XML definitions
      operationId: annotation.serveBulk
      x-api-path-slug: serviceannotation-annotationactionservebulk-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[codeEqual]
      - in: query
        name: filter[codeIn]
      - in: query
        name: filter[codeLike]
      - in: query
        name: filter[codeMultiLikeAnd]
      - in: query
        name: filter[codeMultiLikeOr]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[cuePointTypeEqual]
        description: 'Enum Type: `KalturaCuePointType`'
      - in: query
        name: filter[cuePointTypeIn]
      - in: query
        name: filter[descriptionLike]
      - in: query
        name: filter[descriptionMultiLikeAnd]
      - in: query
        name: filter[descriptionMultiLikeOr]
      - in: query
        name: filter[durationGreaterThanOrEqual]
      - in: query
        name: filter[durationLessThanOrEqual]
      - in: query
        name: filter[endTimeGreaterThanOrEqual]
      - in: query
        name: filter[endTimeLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[eventTypeEqual]
        description: 'Enum Type: `KalturaEventType`'
      - in: query
        name: filter[eventTypeIn]
      - in: query
        name: filter[forceStopEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[isPublicEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentIdEqual]
      - in: query
        name: filter[parentIdIn]
      - in: query
        name: filter[partnerSortValueEqual]
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueIn]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[protocolTypeEqual]
        description: 'Enum Type: `KalturaAdProtocolType`'
      - in: query
        name: filter[protocolTypeIn]
      - in: query
        name: filter[questionLike]
      - in: query
        name: filter[questionMultiLikeAnd]
      - in: query
        name: filter[questionMultiLikeOr]
      - in: query
        name: filter[quizUserEntryIdEqual]
      - in: query
        name: filter[quizUserEntryIdIn]
      - in: query
        name: filter[startTimeGreaterThanOrEqual]
      - in: query
        name: filter[startTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCuePointStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[subTypeEqual]
        description: 'Enum Type: `KalturaThumbCuePointSubType`'
      - in: query
        name: filter[subTypeIn]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: filter[tagsLike]
      - in: query
        name: filter[tagsMultiLikeAnd]
      - in: query
        name: filter[tagsMultiLikeOr]
      - in: query
        name: filter[textLike]
      - in: query
        name: filter[textMultiLikeAnd]
      - in: query
        name: filter[textMultiLikeOr]
      - in: query
        name: filter[titleLike]
      - in: query
        name: filter[titleMultiLikeAnd]
      - in: query
        name: filter[titleMultiLikeOr]
      - in: query
        name: filter[triggeredAtGreaterThanOrEqual]
      - in: query
        name: filter[triggeredAtLessThanOrEqual]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[userIdCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqualCurrent]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[userIdEqual]
      - in: query
        name: filter[userIdIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - ServeBulk
  /service/annotation_annotation/action/update:
    get:
      summary: Get Service Annotation Annotation Action Update
      description: Update annotation by id
      operationId: annotation.update
      x-api-path-slug: serviceannotation-annotationactionupdate-get
      parameters:
      - in: query
        name: annotation[adType]
        description: 'Enum Type: `KalturaAdType`'
      - in: query
        name: annotation[answerKey]
      - in: query
        name: annotation[assetId]
      - in: query
        name: annotation[code]
      - in: query
        name: annotation[correctAnswerKeys]
      - in: query
        name: annotation[description]
      - in: query
        name: annotation[duration]
        description: Duration in milliseconds
      - in: query
        name: annotation[endTime]
        description: End time in milliseconds
      - in: query
        name: annotation[entryId]
        description: '`insertOnly`'
      - in: query
        name: annotation[eventType]
        description: 'Enum Type: `KalturaEventType`'
      - in: query
        name: annotation[explanation]
      - in: query
        name: annotation[forceStop]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: annotation[hint]
      - in: query
        name: annotation[isPublic]
        description: 'Enum Type: `KalturaNullableBoolean`Is the annotation public'
      - in: query
        name: annotation[objectType]
      - in: query
        name: annotation[optionalAnswers]
      - in: query
        name: annotation[parentId]
        description: '`insertOnly`'
      - in: query
        name: annotation[partnerData]
      - in: query
        name: annotation[partnerSortValue]
      - in: query
        name: annotation[protocolType]
        description: '`insertOnly`Enum Type: `KalturaAdProtocolType`'
      - in: query
        name: annotation[question]
      - in: query
        name: annotation[quizUserEntryId]
        description: '`insertOnly`'
      - in: query
        name: annotation[searchableOnEntry]
        description: 'Enum Type: `KalturaNullableBoolean`Should the cue point get
          indexed on the entry'
      - in: query
        name: annotation[sourceUrl]
      - in: query
        name: annotation[startTime]
        description: Start time in milliseconds
      - in: query
        name: annotation[subType]
        description: 'Enum Type: `KalturaThumbCuePointSubType`The sub type of the
          ThumbCuePoint'
      - in: query
        name: annotation[systemName]
      - in: query
        name: annotation[tags]
      - in: query
        name: annotation[text]
      - in: query
        name: annotation[thumbOffset]
      - in: query
        name: annotation[title]
      - in: query
        name: annotation[triggeredAt]
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - Update
  /service/annotation_annotation/action/updateStatus:
    get:
      summary: Get Service Annotation Annotation Action Updatestatus
      description: Update cuePoint status by id
      operationId: annotation.updateStatus
      x-api-path-slug: serviceannotation-annotationactionupdatestatus-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      - in: query
        name: status
        description: 'Enum Type: `KalturaCuePointStatus`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Annotation
      - Annotation
      - Action
      - UpdateStatus
  /service/apptoken/action/add:
    get:
      summary: Get Service Apptoken Action Add
      description: Add new application authentication token
      operationId: appToken.add
      x-api-path-slug: serviceapptokenactionadd-get
      parameters:
      - in: query
        name: appToken[expiry]
        description: Expiry time of current token (unix timestamp in seconds)
      - in: query
        name: appToken[hashType]
        description: 'Enum Type: `KalturaAppTokenHashType`'
      - in: query
        name: appToken[sessionDuration]
        description: Expiry duration of KS (Kaltura Session) that created using the
          current token (in seconds)
      - in: query
        name: appToken[sessionPrivileges]
        description: Comma separated privileges to be applied on KS (Kaltura Session)
          that created using the current token
      - in: query
        name: appToken[sessionType]
        description: 'Enum Type: `KalturaSessionType`Type of KS (Kaltura Session)
          that created using the current token'
      - in: query
        name: appToken[sessionUserId]
        description: User id of KS (Kaltura Session) that created using the current
          token
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Apptoken
      - Action
      - Add
  /service/apptoken/action/delete:
    get:
      summary: Get Service Apptoken Action Delete
      description: Delete application authentication token by id
      operationId: appToken.delete
      x-api-path-slug: serviceapptokenactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Apptoken
      - Action
      - Delete
  /service/apptoken/action/get:
    get:
      summary: Get Service Apptoken Action Get
      description: Get application authentication token by id
      operationId: appToken.get
      x-api-path-slug: serviceapptokenactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Apptoken
      - Action
      - Get
  /service/apptoken/action/list:
    get:
      summary: Get Service Apptoken Action List
      description: List application authentication tokens by filter and pager
      operationId: appToken.list
      x-api-path-slug: serviceapptokenactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaAppTokenStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Apptoken
      - Action
      - List
  /service/apptoken/action/startSession:
    get:
      summary: Get Service Apptoken Action Startsession
      description: Starts a new KS (kaltura Session) based on application authentication
        token id
      operationId: appToken.startSession
      x-api-path-slug: serviceapptokenactionstartsession-get
      parameters:
      - in: query
        name: expiry
        description: session expiry (in seconds), could be overwritten by shorter
          expiry of the application token and the session-expiry that defined on the
          application token
      - in: query
        name: id
        description: application token id
      - in: query
        name: No Name
      - in: query
        name: tokenHash
        description: hashed token, built of sha1 on current KS concatenated with the
          application token
      - in: query
        name: type
        description: 'Enum Type: `KalturaSessionType`session type, will be ignored
          if a different session type already defined on the application token'
      - in: query
        name: userId
        description: session user id, will be ignored if a different user id already
          defined on the application token
      responses:
        200:
          description: OK
      tags:
      - Service
      - Apptoken
      - Action
      - StartSession
  /service/apptoken/action/update:
    get:
      summary: Get Service Apptoken Action Update
      description: Update application authentication token by id
      operationId: appToken.update
      x-api-path-slug: serviceapptokenactionupdate-get
      parameters:
      - in: query
        name: appToken[expiry]
        description: Expiry time of current token (unix timestamp in seconds)
      - in: query
        name: appToken[hashType]
        description: 'Enum Type: `KalturaAppTokenHashType`'
      - in: query
        name: appToken[sessionDuration]
        description: Expiry duration of KS (Kaltura Session) that created using the
          current token (in seconds)
      - in: query
        name: appToken[sessionPrivileges]
        description: Comma separated privileges to be applied on KS (Kaltura Session)
          that created using the current token
      - in: query
        name: appToken[sessionType]
        description: 'Enum Type: `KalturaSessionType`Type of KS (Kaltura Session)
          that created using the current token'
      - in: query
        name: appToken[sessionUserId]
        description: User id of KS (Kaltura Session) that created using the current
          token
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Apptoken
      - Action
      - Update
  /service/aspera_aspera/action/getFaspUrl:
    get:
      summary: Get Service Aspera Aspera Action Getfaspurl
      description: ""
      operationId: aspera.getFaspUrl
      x-api-path-slug: serviceaspera-asperaactiongetfaspurl-get
      parameters:
      - in: query
        name: flavorAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Aspera
      - Aspera
      - Action
      - GetFaspUrl
  /service/attachment_attachmentasset/action/add:
    get:
      summary: Get Service Attachment Attachmentasset Action Add
      description: Add attachment asset
      operationId: attachmentAsset.add
      x-api-path-slug: serviceattachment-attachmentassetactionadd-get
      parameters:
      - in: query
        name: attachmentAsset[accuracy]
        description: The accuracy of the transcript - values between 0 and 1
      - in: query
        name: attachmentAsset[actualSourceAssetParamsIds]
        description: Comma separated list of source flavor params ids
      - in: query
        name: attachmentAsset[fileExt]
        description: '`insertOnly`The file extension'
      - in: query
        name: attachmentAsset[filename]
        description: The filename of the attachment asset content
      - in: query
        name: attachmentAsset[format]
        description: 'Enum Type: `KalturaAttachmentType`The attachment format'
      - in: query
        name: attachmentAsset[humanVerified]
        description: 'Enum Type: `KalturaNullableBoolean`Was verified by human or
          machine'
      - in: query
        name: attachmentAsset[language]
        description: 'Enum Type: `KalturaLanguage`The language of the transcript'
      - in: query
        name: attachmentAsset[objectType]
      - in: query
        name: attachmentAsset[partnerData]
        description: Partner private data
      - in: query
        name: attachmentAsset[partnerDescription]
        description: Partner friendly description
      - in: query
        name: attachmentAsset[providerType]
        description: 'Enum Type: `KalturaTranscriptProviderType`The provider of the
          transcript'
      - in: query
        name: attachmentAsset[tags]
        description: Tags used to identify the Flavor Asset in various scenarios
      - in: query
        name: attachmentAsset[title]
        description: Attachment asset title
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attachment
      - Attachmentasset
      - Action
      - Add
  /service/attachment_attachmentasset/action/delete:
    get:
      summary: Get Service Attachment Attachmentasset Action Delete
      description: ""
      operationId: attachmentAsset.delete
      x-api-path-slug: serviceattachment-attachmentassetactiondelete-get
      parameters:
      - in: query
        name: attachmentAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attachment
      - Attachmentasset
      - Action
      - Delete
  /service/attachment_attachmentasset/action/get:
    get:
      summary: Get Service Attachment Attachmentasset Action Get
      description: ""
      operationId: attachmentAsset.get
      x-api-path-slug: serviceattachment-attachmentassetactionget-get
      parameters:
      - in: query
        name: attachmentAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attachment
      - Attachmentasset
      - Action
      - Get
  /service/attachment_attachmentasset/action/getRemotePaths:
    get:
      summary: Get Service Attachment Attachmentasset Action Getremotepaths
      description: Get remote storage existing paths for the asset
      operationId: attachmentAsset.getRemotePaths
      x-api-path-slug: serviceattachment-attachmentassetactiongetremotepaths-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attachment
      - Attachmentasset
      - Action
      - GetRemotePaths
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---