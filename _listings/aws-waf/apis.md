---
name: AWS WAF
x-slug: aws-waf
description: AWS WAF is a web application firewall that helps protect your webapplications
  from common web exploits that could affect applicationavailability, compromise security,
  or consume excessive resources. AWSWAF gives you control over which traffic to allow
  or block to your webapplications by defining customizable web security rules. You
  can use AWSWAF to create custom rules that block common attack patterns, such as
  SQLinjection or cross-site scripting, and rules that are designed for your specific
  application. New rules can be deployed within minutes, letting you respondquickly
  to changing traffic patterns. Also, AWS WAF includes a full-featuredAPI that you
  can use to automate the creation, deployment, and maintenanceof web security rules.With
  AWS WAF you pay only for what you use. AWS WAF pricing is based on how many rules
  you deploy and how many web requests your web application receives. There are no
  upfront commitments.You can deploy AWS WAF on either Amazon CloudFront as part of
  your CDN solution or the Application Load Balancer (ALB) that fronts your web servers
  or origin servers running on EC2.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/apis.md
specificationVersion: "0.14"
apis:
- name: AWS WAF API - Associate Web ACL
  x-api-slug: actionassociatewebacl-get
  description: 'Service: AWS WAF RegionalAssociates a web ACL with a resource.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionassociatewebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionassociatewebacl-get-openapi.md
- name: AWS WAF API - Create Byte Match Set
  x-api-slug: actioncreatebytematchset-get
  description: 'Service: AWS WAFCreates a ByteMatchSet.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatebytematchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatebytematchset-get-openapi.md
- name: AWS WAF API - Create IP Set
  x-api-slug: actioncreateipset-get
  description: 'Service: AWS WAFCreates an.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreateipset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreateipset-get-openapi.md
- name: AWS WAF API - Create Size Constraint Set
  x-api-slug: actioncreatesizeconstraintset-get
  description: 'Service: AWS WAFCreates a SizeConstraintSet.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatesizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatesizeconstraintset-get-openapi.md
- name: AWS WAF API - Create Sql Injection Match Set
  x-api-slug: actioncreatesqlinjectionmatchset-get
  description: 'Service: AWS WAFCreates a.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatesqlinjectionmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatesqlinjectionmatchset-get-openapi.md
- name: AWS WAF API - Create Web ACL
  x-api-slug: actioncreatewebacl-get
  description: 'Service: AWS WAFCreates a WebACL, which contains the Rules that identify
    the CloudFront web requests that you want to allow, block, or count.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatewebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatewebacl-get-openapi.md
- name: AWS WAF API - Create XSS Match Set
  x-api-slug: actioncreatexssmatchset-get
  description: 'Service: AWS WAFCreates an.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatexssmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actioncreatexssmatchset-get-openapi.md
- name: AWS WAF API - Delete Byte Match Set
  x-api-slug: actiondeletebytematchset-get
  description: 'Service: AWS WAFPermanently deletes a.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletebytematchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletebytematchset-get-openapi.md
- name: AWS WAF API - Delete IP Set
  x-api-slug: actiondeleteipset-get
  description: 'Service: AWS WAFPermanently deletes an.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeleteipset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeleteipset-get-openapi.md
- name: AWS WAF API - Delete Size Constraint Set
  x-api-slug: actiondeletesizeconstraintset-get
  description: 'Service: AWS WAFPermanently deletes a.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletesizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletesizeconstraintset-get-openapi.md
- name: AWS WAF API - Delete Sql Injection Match Set
  x-api-slug: actiondeletesqlinjectionmatchset-get
  description: 'Service: AWS WAFPermanently deletes a.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletesqlinjectionmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletesqlinjectionmatchset-get-openapi.md
- name: AWS WAF API - Delete Web ACL
  x-api-slug: actiondeletewebacl-get
  description: 'Service: AWS WAFPermanently deletes a.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletewebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletewebacl-get-openapi.md
- name: AWS WAF API - Delete Xss Match Set
  x-api-slug: actiondeletexssmatchset-get
  description: 'Service: AWS WAFPermanently deletes an.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletexssmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondeletexssmatchset-get-openapi.md
- name: AWS WAF API - Disassociate Web ACL
  x-api-slug: actiondisassociatewebacl-get
  description: 'Service: AWS WAF RegionalRemoves a web ACL from the specified resource.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondisassociatewebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiondisassociatewebacl-get-openapi.md
- name: AWS WAF API - Get Byte Match Set
  x-api-slug: actiongetbytematchset-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetbytematchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetbytematchset-get-openapi.md
- name: AWS WAF API - Get Change Token
  x-api-slug: actiongetchangetoken-get
  description: 'Service: AWS WAFWhen you want to create, update, or delete AWS WAF
    objects, get a change token and include the change token in the create, update,
    or delete request.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetchangetoken-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetchangetoken-get-openapi.md
- name: AWS WAF API - Get Change Token Status
  x-api-slug: actiongetchangetokenstatus-get
  description: 'Service: AWS WAFReturns the status of a ChangeToken that you got by
    calling.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetchangetokenstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetchangetokenstatus-get-openapi.md
- name: AWS WAF API - Get IP Set
  x-api-slug: actiongetipset-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetipset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetipset-get-openapi.md
- name: AWS WAF API - Get Sampled Requests
  x-api-slug: actiongetsampledrequests-get
  description: 'Service: AWS WAFGets detailed information about a specified number
    of requests--a sample--that AWS WAF randomly selects from among the first 5,000
    requests that your AWS resource received during a time range that you choose.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetsampledrequests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetsampledrequests-get-openapi.md
- name: AWS WAF API - Get Size Constraint Set
  x-api-slug: actiongetsizeconstraintset-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetsizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetsizeconstraintset-get-openapi.md
- name: AWS WAF API - Get Sql Injection Match Set
  x-api-slug: actiongetsqlinjectionmatchset-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetsqlinjectionmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetsqlinjectionmatchset-get-openapi.md
- name: AWS WAF API - Get Web ACL
  x-api-slug: actiongetwebacl-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetwebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetwebacl-get-openapi.md
- name: AWS WAF API - Get Web ACLFor Resource
  x-api-slug: actiongetwebaclforresource-get
  description: 'Service: AWS WAF RegionalReturns the web ACL for the specified resource.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetwebaclforresource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetwebaclforresource-get-openapi.md
- name: AWS WAF API - Get Xss Match Set
  x-api-slug: actiongetxssmatchset-get
  description: 'Service: AWS WAFReturns the.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetxssmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actiongetxssmatchset-get-openapi.md
- name: AWS WAF API - List Byte Match Sets
  x-api-slug: actionlistbytematchsets-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistbytematchsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistbytematchsets-get-openapi.md
- name: AWS WAF API - List IP Sets
  x-api-slug: actionlistipsets-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistipsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistipsets-get-openapi.md
- name: AWS WAF API - List Resources For Web ACL
  x-api-slug: actionlistresourcesforwebacl-get
  description: 'Service: AWS WAF RegionalReturns an array of resources associated
    with the specified web ACL.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistresourcesforwebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistresourcesforwebacl-get-openapi.md
- name: AWS WAF API - List Size Constraint Sets
  x-api-slug: actionlistsizeconstraintsets-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistsizeconstraintsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistsizeconstraintsets-get-openapi.md
- name: AWS WAF API - List SQL Injection Match Sets
  x-api-slug: actionlistsqlinjectionmatchsets-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistsqlinjectionmatchsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistsqlinjectionmatchsets-get-openapi.md
- name: AWS WAF API - List Web ACLs
  x-api-slug: actionlistwebacls-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistwebacls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistwebacls-get-openapi.md
- name: AWS WAF API - List Xss Match Sets
  x-api-slug: actionlistxssmatchsets-get
  description: 'Service: AWS WAFReturns an array of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistxssmatchsets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionlistxssmatchsets-get-openapi.md
- name: AWS WAF API - Update Byte Match Set
  x-api-slug: actionupdatebytematchset-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatebytematchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatebytematchset-get-openapi.md
- name: AWS WAF API - Update IP Set
  x-api-slug: actionupdateipset-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdateipset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdateipset-get-openapi.md
- name: AWS WAF API - Update Size Constraint Set
  x-api-slug: actionupdatesizeconstraintset-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatesizeconstraintset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatesizeconstraintset-get-openapi.md
- name: AWS WAF API - Update SQL Injection Match Set
  x-api-slug: actionupdatesqlinjectionmatchset-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatesqlinjectionmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatesqlinjectionmatchset-get-openapi.md
- name: AWS WAF API - Update Web ACL
  x-api-slug: actionupdatewebacl-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatewebacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatewebacl-get-openapi.md
- name: AWS WAF API - Update Xss Match Set
  x-api-slug: actionupdatexssmatchset-get
  description: 'Service: AWS WAFInserts or deletes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: https://aws.amazon.com/waf/
  baseURL: :///
  tags: Amazon Web Services, Security, Firewall, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatexssmatchset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-waf/actionupdatexssmatchset-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.storage.gateway.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.waf.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/waf/faq/
- type: x-getting-started
  url: https://aws.amazon.com/waf/getting-started/
- type: x-partners
  url: https://aws.amazon.com/waf/partners/
- type: x-pricing
  url: https://aws.amazon.com/waf/pricing/
- type: x-tutorials
  url: https://aws.amazon.com/waf/preconfiguredrules/
- type: x-webinars
  url: https://aws.amazon.com/waf/webinars/
- type: x-website
  url: https://aws.amazon.com/waf/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---