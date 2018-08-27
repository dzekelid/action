---
swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 0
info:
  title: Amazon Lightsale API Delete Domain Entry
  version: 1.0.0
  description: Deletes a specific domain entry.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AllocateStaticIp:
    get:
      summary: Allocate Static Ip
      description: Allocates a static IP address.
      operationId: allocateStaticIp
      x-api-path-slug: actionallocatestaticip-get
      parameters:
      - in: query
        name: staticIpName
        description: The name of the static IP address
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Addresses
  /?Action=AttachStaticIp:
    get:
      summary: Attach Static Ip
      description: Attaches a static IP address to a specific Amazon Lightsail instance.
      operationId: attachStaticIp
      x-api-path-slug: actionattachstaticip-get
      parameters:
      - in: query
        name: instanceName
        description: The instance name to which you want to attach the static IP address
        type: string
      - in: query
        name: staticIpName
        description: The name of the static IP
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Addresses
  /?Action=CloseInstancePublicPorts:
    get:
      summary: Close Instance Public Ports
      description: Closes the public ports on a specific Amazon Lightsail instance.
      operationId: closeInstancePublicPorts
      x-api-path-slug: actioncloseinstancepublicports-get
      parameters:
      - in: query
        name: instanceName
        description: The name of the instance on which youre attempting to close the
          public      ports
        type: string
      - in: query
        name: portInfo
        description: Information about the public port you are trying to close
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=CreateDomain:
    get:
      summary: Create Domain
      description: Creates a domain resource for the specified domain (e.
      operationId: createDomain
      x-api-path-slug: actioncreatedomain-get
      parameters:
      - in: query
        name: domainName
        description: The domain name to manage (e
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /?Action=CreateDomainEntry:
    get:
      summary: Create Domain Entry
      description: |-
        Creates one of the following entry records associated with the domain: A record, CNAME
              record, TXT record, or MX record.
      operationId: createDomainEntry
      x-api-path-slug: actioncreatedomainentry-get
      parameters:
      - in: query
        name: domainEntry
        description: An array of key-value pairs containing information about the
          domain entry      request
        type: string
      - in: query
        name: domainName
        description: The domain name (e
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /?Action=CreateInstances:
    get:
      summary: Create Instances
      description: |-
        Creates one or more Amazon Lightsail virtual private servers, or
                instances.
      operationId: createInstances
      x-api-path-slug: actioncreateinstances-get
      parameters:
      - in: query
        name: availabilityZone
        description: The Availability Zone in which to create your instance
        type: string
      - in: query
        name: blueprintId
        description: The ID for a virtual private server image (e
        type: string
      - in: query
        name: bundleId
        description: The bundle of specification information for your virtual private
          server (or        instance), including the pricing plan (e
        type: string
      - in: query
        name: customImageName
        description: The name for your custom image
        type: string
      - in: query
        name: instanceNames
        description: The names to use for your new Lightsail instances
        type: string
      - in: query
        name: keyPairName
        description: The name of your key pair
        type: string
      - in: query
        name: userData
        description: A launch script you can create that configures a server with
          additional user data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=CreateInstancesFromSnapshot:
    get:
      summary: Create Instances From Snapshot
      description: |-
        Uses a specific snapshot as a blueprint for creating one or more new instances that are
              based on that identical configuration.
      operationId: createInstancesFromSnapshot
      x-api-path-slug: actioncreateinstancesfromsnapshot-get
      parameters:
      - in: query
        name: availabilityZone
        description: The Availability Zone where you want to create your instances
        type: string
      - in: query
        name: bundleId
        description: The bundle of specification information for your virtual private
          server (or        instance), including the pricing plan (e
        type: string
      - in: query
        name: instanceNames
        description: The names for your new instances
        type: string
      - in: query
        name: instanceSnapshotName
        description: The name of the instance snapshot on which you are basing your
          new instances
        type: string
      - in: query
        name: keyPairName
        description: The name for your key pair
        type: string
      - in: query
        name: userData
        description: You can create a launch script that configures a server with
          additional user data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=CreateInstanceSnapshot:
    get:
      summary: Create Instance Snapshot
      description: |-
        Creates a snapshot of a specific virtual private server, or
                instance.
      operationId: createInstanceSnapshot
      x-api-path-slug: actioncreateinstancesnapshot-get
      parameters:
      - in: query
        name: instanceName
        description: The Lightsail instance on which to base your snapshot
        type: string
      - in: query
        name: instanceSnapshotName
        description: The name for your new snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
  /?Action=CreateKeyPair:
    get:
      summary: Create Key Pair
      description: Creates sn SSH key pair.
      operationId: createKeyPair
      x-api-path-slug: actioncreatekeypair-get
      parameters:
      - in: query
        name: keyPairName
        description: The name for your new key pair
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key Pairs
  /?Action=DeleteDomain:
    get:
      summary: Delete Domain
      description: Deletes the specified domain recordset and all of its domain records.
      operationId: deleteDomain
      x-api-path-slug: actiondeletedomain-get
      parameters:
      - in: query
        name: domainName
        description: The specific domain name to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /?Action=DeleteDomainEntry:
    get:
      summary: Delete Domain Entry
      description: Deletes a specific domain entry.
      operationId: deleteDomainEntry
      x-api-path-slug: actiondeletedomainentry-get
      parameters:
      - in: query
        name: domainEntry
        description: An array of key-value pairs containing information about your
          domain entries
        type: string
      - in: query
        name: domainName
        description: The name of the domain entry to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Domains
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