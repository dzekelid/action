---
swagger: "2.0"
x-collection-name: AWS OpsWorks
x-complete: 0
info:
  title: AWS OpsWorks API Attach Elastic Load Balancer
  version: 1.0.0
  description: Attaches an Elastic Load Balancing load balancer to a specified layer.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AssignInstance:
    get:
      summary: Assign Instance
      description: Assign a registered instance to a layer.
      operationId: assignInstance
      x-api-path-slug: actionassigninstance-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: LayerIds
        description: The layer ID, which must correspond to a custom layer
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assign
      - Instance
  /?Action=AssignVolume:
    get:
      summary: Assign Volume
      description: Assigns one of the stack's registered Amazon EBS volumes to a specified
        instance.
      operationId: assignVolume
      x-api-path-slug: actionassignvolume-get
      parameters:
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      - in: query
        name: VolumeId
        description: The volume ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Assign
      - Volume
  /?Action=AssociateElasticIp:
    get:
      summary: Associate Elastic IP
      description: Associates one of the stack's registered Elastic IP addresses with
        a specified instance.
      operationId: associateElasticIp
      x-api-path-slug: actionassociateelasticip-get
      parameters:
      - in: query
        name: ElasticIp
        description: The Elastic IP address
        type: string
      - in: query
        name: InstanceId
        description: The instance ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Associate
      - Elastic
      - IP Addresses
  /?Action=AttachElasticLoadBalancer:
    get:
      summary: Attach Elastic Load Balancer
      description: Attaches an Elastic Load Balancing load balancer to a specified
        layer.
      operationId: attachElasticLoadBalancer
      x-api-path-slug: actionattachelasticloadbalancer-get
      parameters:
      - in: query
        name: ElasticLoadBalancerName
        description: The Elastic Load Balancing instances name
        type: string
      - in: query
        name: LayerId
        description: The ID of the layer that the Elastic Load Balancing instance
          is to be attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attach
      - Elastic
      - Load
      - Balancer
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