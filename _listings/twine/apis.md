---
name: Twine
x-slug: twine
description: 'Twine Health is a cloud-based collaborative care platform for chronic
  disease management. It consists of a patient engagement portal, a peer support network,
  a care management solution, and an outcome analytics tool. The platform enables
  users to co-create personalized care plans that serve as common ground for collaboration
  with their care team: their own providers such as physicians and nurse practitioners;
  their family and friends; and coaches such as nurses, pharmacists, health coaches,
  and more.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/twinehealth.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/twine/apis.md
specificationVersion: "0.14"
apis:
- name: Twine - Create action
  x-api-slug: action-post
  description: Create a plan action
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/twinehealth.png
  humanURL: http://twinehealth.com
  baseURL: https://api.twinehealth.com//pub
  tags: Wearables, Healthcare, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/twine/action-post-openapi.md
- name: Twine - Get an action
  x-api-slug: actionid-get
  description: Get a health action from a patient's plan.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/twinehealth.png
  humanURL: http://twinehealth.com
  baseURL: https://api.twinehealth.com//pub
  tags: Wearables, Healthcare, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/twine/actionid-get-openapi.md
- name: Twine - Update an action
  x-api-slug: actionid-patch
  description: Update a health action from a patient's plan.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/twinehealth.png
  humanURL: http://twinehealth.com
  baseURL: https://api.twinehealth.com//pub
  tags: Wearables, Healthcare, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/twine/actionid-patch-openapi.md
x-common:
- type: x-api-gallery
  url: http://twilio.api.gallery.streamdata.io
- type: x-api-stack
  url: http://twine.stack.network
- type: x-authentication
  url: http://developer.twinehealth.com/#section/Authentication
- type: x-developer
  url: http://developer.twinehealth.com/
- type: x-website
  url: http://twinehealth.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---