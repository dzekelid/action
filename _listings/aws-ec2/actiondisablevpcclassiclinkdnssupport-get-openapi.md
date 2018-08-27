---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Disable Vpc Classic Link Dns Support
  version: 1.0.0
  description: Disables ClassicLink DNS support for a VPC.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AcceptReservedInstancesExchangeQuote:
    get:
      summary: Accept Reserved Instances Exchange Quote
      description: Accepts the Convertible Reserved Instance exchange quote described
        in the GetReservedInstancesExchangeQuote call.
      operationId: acceptreservedinstancesexchangequote
      x-api-path-slug: actionacceptreservedinstancesexchangequote-get
      parameters:
      - in: query
        name: ReservedInstancesListingId
        description: The ID of the Reserved Instance listing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=AcceptVpcPeeringConnection:
    get:
      summary: Accept Vpc Peering Connection
      description: Accept a VPC peering connection request.
      operationId: acceptvpcpeeringconnection
      x-api-path-slug: actionacceptvpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: PeerOwnerId
        description: The AWS account ID of the owner of the peer VPC
        type: string
      - in: query
        name: PeerVpcId
        description: The ID of the VPC with which you are creating the VPC peering
          connection
        type: string
      - in: query
        name: VpcId
        description: The ID of the requester VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=AllocateAddress:
    get:
      summary: Allocate Address
      description: Acquires an Elastic IP address.
      operationId: allocateaddress
      x-api-path-slug: actionallocateaddress-get
      parameters:
      - in: query
        name: AllocationId
        description: '[EC2-VPC] The allocation ID'
        type: string
      - in: query
        name: AllowReassociation
        description: '[EC2-VPC] For a VPC in an EC2-Classic account, specify true
          to allow an Elastic IP address that is already associated with an instance
          or network interface to be reassociated with the specified instance or network
          interface'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: NetworkInterfaceId
        description: '[EC2-VPC] The ID of the network interface'
        type: string
      - in: query
        name: PrivateIpAddress
        description: '[EC2-VPC] The primary or secondary private IP address to associate
          with the Elastic IP address'
        type: string
      - in: query
        name: PublicIp
        description: The Elastic IP address
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=AllocateHosts:
    get:
      summary: Allocate Hosts
      description: Allocates a Dedicated Host to your account.
      operationId: allocatehosts
      x-api-path-slug: actionallocatehosts-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: HostId.N
        description: The IDs of the Dedicated Hosts
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host
  /?Action=AssignIpv6Addresses:
    get:
      summary: Assign Ipv6 Addresses
      description: Assigns one or more IPv6 addresses to the specified network interface.
      operationId: assignipv6addresses
      x-api-path-slug: actionassignipv6addresses-get
      parameters:
      - in: query
        name: AllowReassignment
        description: Indicates whether to allow an IP address that is already assigned
          to another network interface or instance to be reassigned to the specified
          network interface
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of the network interface
        type: string
      - in: query
        name: PrivateIpAddress.N
        description: One or more IP addresses to be assigned as a secondary private
          IP address to the network interface
        type: string
      - in: query
        name: SecondaryPrivateIpAddressCount
        description: The number of secondary IP addresses to assign to the network
          interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=AssignPrivateIpAddresses:
    get:
      summary: Assign Private Ip Addresses
      description: Assigns one or more secondary private IP addresses to the specified
        network interface.
      operationId: assignprivateipaddresses
      x-api-path-slug: actionassignprivateipaddresses-get
      parameters:
      - in: query
        name: DeviceIndex
        description: The index of the device for the network interface attachment
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of the network interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=AssociateAddress:
    get:
      summary: Associate Address
      description: Associates an Elastic IP address with an instance or a network
        interface.
      operationId: associateaddress
      x-api-path-slug: actionassociateaddress-get
      parameters:
      - in: query
        name: AllocationId.N
        description: '[EC2-VPC] One or more allocation IDs'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: PublicIp.N
        description: '[EC2-Classic] One or more Elastic IP addresses'
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=AssociateDhcpOptions:
    get:
      summary: Associate Dhcp Options
      description: Associates a set of DHCP options (that you've previously created)
        with the specified VPC, or associates no DHCP options with the VPC.
      operationId: associatedhcpoptions
      x-api-path-slug: actionassociatedhcpoptions-get
      parameters:
      - in: query
        name: DhcpConfiguration.N
        description: A DHCP configuration option
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=AssociateRouteTable:
    get:
      summary: Associate Route Table
      description: Associates a subnet with a route table.
      operationId: associateroutetable
      x-api-path-slug: actionassociateroutetable-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The IPv4 CIDR address block used for the destination match
        type: string
      - in: query
        name: DestinationIpv6CidrBlock
        description: The IPv6 CIDR block used for the destination match
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EgressOnlyInternetGatewayId
        description: '[IPv6 traffic only] The ID of an egress-only Internet gateway'
        type: string
      - in: query
        name: GatewayId
        description: The ID of an Internet gateway or virtual private gateway attached
          to your VPC
        type: string
      - in: query
        name: InstanceId
        description: The ID of a NAT instance in your VPC
        type: string
      - in: query
        name: NatGatewayId
        description: '[IPv4 traffic only] The ID of a NAT gateway'
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of a network interface
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table for the route
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of a VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=AssociateSubnetCidrBlock:
    get:
      summary: Associate Subnet Cidr Block
      description: Associates a CIDR block with your subnet.
      operationId: associatesubnetcidrblock
      x-api-path-slug: actionassociatesubnetcidrblock-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the subnet
        type: string
      - in: query
        name: CidrBlock
        description: The IPv4 network range for the subnet, in CIDR notation
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Ipv6CidrBlock
        description: The IPv6 network range for the subnet, in CIDR notation
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - CIDR Block
  /?Action=AssociateVpcCidrBlock:
    get:
      summary: Associate Vpc Cidr Block
      description: Associates a CIDR block with your VPC.
      operationId: associatevpccidrblock
      x-api-path-slug: actionassociatevpccidrblock-get
      parameters:
      - in: query
        name: AmazonProvidedIpv6CidrBlock
        description: Requests an Amazon-provided IPv6 CIDR block with a /56 prefix
          length for the VPC
        type: string
      - in: query
        name: CidrBlock
        description: The IPv4 network range for the VPC, in CIDR notation
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceTenancy
        description: The tenancy options for instances launched into the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - CIDR Block
  /?Action=AttachClassicLinkVpc:
    get:
      summary: Attach Classic Link Vpc
      description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
        one or more of the VPC's\n\t\t\tsecurity groups."
      operationId: attachclassiclinkvpc
      x-api-path-slug: actionattachclassiclinkvpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Link
  /?Action=AttachInternetGateway:
    get:
      summary: Attach Internet Gateway
      description: "Attaches an Internet gateway to a VPC, enabling connectivity between
        the Internet\n\t\t\t\tand the VPC."
      operationId: attachinternetgateway
      x-api-path-slug: actionattachinternetgateway-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC for which to create the egress-only Internet
          gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=AttachNetworkInterface:
    get:
      summary: Attach Network Interface
      description: Attaches a network interface to an instance.
      operationId: attachnetworkinterface
      x-api-path-slug: actionattachnetworkinterface-get
      parameters:
      - in: query
        name: Description
        description: A description for the network interface
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Ipv6AddressCount
        description: The number of IPv6 addresses to assign to a network interface
        type: string
      - in: query
        name: Ipv6Addresses.N
        description: One or more specific IPv6 addresses from the IPv6 CIDR block
          range of your subnet
        type: string
      - in: query
        name: PrivateIpAddress
        description: The primary private IPv4 address of the network interface
        type: string
      - in: query
        name: PrivateIpAddresses.N
        description: One or more private IPv4 addresses
        type: string
      - in: query
        name: SecondaryPrivateIpAddressCount
        description: The number of secondary private IPv4 addresses to assign to a
          network interface
        type: string
      - in: query
        name: SecurityGroupId.N
        description: The IDs of one or more security groups
        type: string
      - in: query
        name: SubnetId
        description: The ID of the subnet to associate with the network interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=AttachVolume:
    get:
      summary: Attach Volume
      description: |-
        Attaches an EBS volume to a running or stopped instance and exposes it to the instance with
              the specified device name.
      operationId: attachvolume
      x-api-path-slug: actionattachvolume-get
      parameters:
      - in: query
        name: Description
        description: A description for the EBS snapshot
        type: string
      - in: query
        name: DestinationRegion
        description: The destination region to use in the PresignedUrl parameter of
          a snapshot copy      operation
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Encrypted
        description: Specifies whether the destination snapshot should be encrypted
        type: string
      - in: query
        name: KmsKeyId
        description: The full ARN of the AWS Key Management Service (AWS KMS) CMK
          to use when creating the snapshot copy
        type: string
      - in: query
        name: PresignedUrl
        description: The pre-signed URL that facilitates copying an encrypted snapshot
        type: string
      - in: query
        name: SourceRegion
        description: The ID of the region that contains the snapshot to be copied
        type: string
      - in: query
        name: SourceSnapshotId
        description: The ID of the EBS snapshot to copy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive Volume
  /?Action=AttachVpnGateway:
    get:
      summary: Attach Vpn Gateway
      description: Attaches a virtual private gateway to a VPC.
      operationId: attachvpngateway
      x-api-path-slug: actionattachvpngateway-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the virtual private gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Type
        description: The type of VPN connection this virtual private gateway supports
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
  /?Action=AuthorizeSecurityGroupEgress (EC2-VPC only):
    get:
      summary: Authorize Security Group Egress ( E C2- V P C only)
      description: '[EC2-VPC only] Adds one or more egress rules to a security group
        for use with a VPC.'
      operationId: authorizesecuritygroupegress-ec2vpc-only
      x-api-path-slug: actionauthorizesecuritygroupegress-ec2vpc-only-get
      parameters:
      - in: query
        name: CidrIp
        description: The CIDR IPv4 address range
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: FromPort
        description: The start of port range for the TCP and UDP protocols, or an
          ICMP/ICMPv6 type number
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: GroupName
        description: '[EC2-Classic, default VPC] The name of the security group'
        type: string
      - in: query
        name: IpPermissions.N
        description: A set of IP permissions
        type: string
      - in: query
        name: IpProtocol
        description: The IP protocol name (tcp, udp, icmp) or number      (see Protocol
          Numbers)
        type: string
      - in: query
        name: SourceSecurityGroupName
        description: '[EC2-Classic, default VPC] The name of the source security group'
        type: string
      - in: query
        name: SourceSecurityGroupOwnerId
        description: '[EC2-Classic] The AWS account number for the source security
          group, if the source security group is in a different account'
        type: string
      - in: query
        name: ToPort
        description: The end of port range for the TCP and UDP protocols, or an ICMP/ICMPv6
          code number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=AuthorizeSecurityGroupIngress:
    get:
      summary: Authorize Security Group Ingress
      description: Adds one or more ingress rules to a security group.
      operationId: authorizesecuritygroupingress
      x-api-path-slug: actionauthorizesecuritygroupingress-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: GroupDescription
        description: A description for the security group
        type: string
      - in: query
        name: GroupName
        description: The name of the security group
        type: string
      - in: query
        name: VpcId
        description: '[EC2-VPC] The ID of the VPC'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=BundleInstance:
    get:
      summary: Bundle Instance
      description: Bundles an Amazon instance store-backed Windows instance.
      operationId: bundleinstance
      x-api-path-slug: actionbundleinstance-get
      parameters:
      - in: query
        name: BundleId
        description: The ID of the bundle task
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Instance
  /?Action=CancelBundleTask:
    get:
      summary: Cancel Bundle Task
      description: Cancels a bundling operation for an instance store-backed Windows
        instance.
      operationId: cancelbundletask
      x-api-path-slug: actioncancelbundletask-get
      parameters:
      - in: query
        name: BundleId.N
        description: One or more bundle task IDs
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Task
  /?Action=CancelConversionTask:
    get:
      summary: Cancel Conversion Task
      description: Cancels an active conversion task.
      operationId: cancelconversiontask
      x-api-path-slug: actioncancelconversiontask-get
      responses:
        200:
          description: OK
      tags:
      - Bundle Task
  /?Action=CancelExportTask:
    get:
      summary: Cancel Export Task
      description: Cancels an active export task.
      operationId: cancelexporttask
      x-api-path-slug: actioncancelexporttask-get
      parameters:
      - in: query
        name: Description
        description: A description for the conversion task or the resource being exported
        type: string
      - in: query
        name: ExportToS3
        description: The format and location for an instance export task
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: TargetEnvironment
        description: The target virtualization environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Export Task
  /?Action=CancelImportTask:
    get:
      summary: Cancel Import Task
      description: Cancels an in-process import virtual machine or import snapshot
        task.
      operationId: cancelimporttask
      x-api-path-slug: actioncancelimporttask-get
      parameters:
      - in: query
        name: ConversionTaskId.N
        description: One or more conversion task IDs
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,      and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Import Task
  /?Action=CancelReservedInstancesListing:
    get:
      summary: Cancel Reserved Instances Listing
      description: Cancels the specified Reserved Instance listing in the Reserved
        Instance Marketplace.
      operationId: cancelreservedinstanceslisting
      x-api-path-slug: actioncancelreservedinstanceslisting-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of yourlistings
        type: string
      - in: query
        name: InstanceCount
        description: The number of instances that are a part of a Reserved Instance
          account to be listed in the Reserved Instance Marketplace
        type: string
      - in: query
        name: PriceSchedules.N
        description: A list specifying the price of the Standard Reserved Instance
          for each month remaining in the Reserved Instance term
        type: string
      - in: query
        name: ReservedInstancesId
        description: The ID of the active Standard Reserved Instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instance
  /?Action=CancelSpotFleetRequests:
    get:
      summary: Cancel Spot Fleet Requests
      description: Cancels the specified Spot fleet requests.
      operationId: cancelspotfleetrequests
      x-api-path-slug: actioncancelspotfleetrequests-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: SpotFleetRequestId
        description: The ID of the Spot fleet request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Fleet
  /?Action=CancelSpotInstanceRequests:
    get:
      summary: Cancel Spot Instance Requests
      description: Cancels one or more Spot instance requests.
      operationId: cancelspotinstancerequests
      x-api-path-slug: actioncancelspotinstancerequests-get
      parameters:
      - in: query
        name: Bucket
        description: The Amazon S3 bucket in which to store the Spot instance data
          feed
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Prefix
        description: A prefix for the data feed file names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Instance
  /?Action=ConfirmProductInstance:
    get:
      summary: Confirm Product Instance
      description: Determines whether a product code is associated with an instance.
      operationId: confirmproductinstance
      x-api-path-slug: actionconfirmproductinstance-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to bundle
        type: string
      - in: query
        name: Storage
        description: The bucket in which to store the AMI
        type: string
      responses:
        200:
          description: OK
      tags:
      - Product Instance
  /?Action=CopyImage:
    get:
      summary: Copy Image
      description: Initiates the copy of an AMI from the specified source region to
        the current region.
      operationId: copyimage
      x-api-path-slug: actioncopyimage-get
      parameters:
      - in: query
        name: BlockDeviceMapping.N
        description: Information about one or more block device mappings
        type: string
      - in: query
        name: Description
        description: A description for the new image
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: Name
        description: A name for the new image
        type: string
      - in: query
        name: NoReboot
        description: By default, Amazon EC2 attempts to shut down and reboot the instance
          before creating the image
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=CopySnapshot:
    get:
      summary: Copy Snapshot
      description: Copies a point-in-time snapshot of an EBS volume and stores it
        in Amazon S3.
      operationId: copysnapshot
      x-api-path-slug: actioncopysnapshot-get
      parameters:
      - in: query
        name: Description
        description: A description for the snapshot
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: VolumeId
        description: The ID of the EBS volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive Snapshot
  /?Action=CreateCustomerGateway:
    get:
      summary: Create Customer Gateway
      description: Provides information to AWS about your VPN customer gateway device.
      operationId: createcustomergateway
      x-api-path-slug: actioncreatecustomergateway-get
      parameters:
      - in: query
        name: CustomerGatewayId
        description: The ID of the customer gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gateway
  /?Action=CreateDhcpOptions:
    get:
      summary: Create Dhcp Options
      description: Creates a set of DHCP options for your VPC.
      operationId: createdhcpoptions
      x-api-path-slug: actioncreatedhcpoptions-get
      parameters:
      - in: query
        name: DhcpOptionsId
        description: The ID of the DHCP options set
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=CreateEgressOnlyInternetGateway:
    get:
      summary: Create Egress Only Internet Gateway
      description: '[IPv6 only] Creates an egress-only Internet gateway for your VPC.'
      operationId: createegressonlyinternetgateway
      x-api-path-slug: actioncreateegressonlyinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=CreateFlowLogs:
    get:
      summary: Create Flow Logs
      description: Creates one or more flow logs to capture IP traffic for a specific
        network interface, subnet, or VPC.
      operationId: createflowlogs
      x-api-path-slug: actioncreateflowlogs-get
      parameters:
      - in: query
        name: FlowLogId.N
        description: One or more flow log IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Flow Logs
  /?Action=CreateImage:
    get:
      summary: Create Image
      description: Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance
        that is either running or stopped.
      operationId: createimage
      x-api-path-slug: actioncreateimage-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ImageId
        description: The ID of the AMI
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=CreateInstanceExportTask:
    get:
      summary: Create Instance Export Task
      description: Exports a running or stopped instance to an S3 bucket.
      operationId: createinstanceexporttask
      x-api-path-slug: actioncreateinstanceexporttask-get
      parameters:
      - in: query
        name: ExportTaskId.N
        description: One or more export task IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Export Task
  /?Action=CreateInternetGateway:
    get:
      summary: Create Internet Gateway
      description: Creates an Internet gateway for use with a VPC.
      operationId: createinternetgateway
      x-api-path-slug: actioncreateinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: EgressOnlyInternetGatewayId
        description: The ID of the egress-only Internet gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=CreateKeyPair:
    get:
      summary: Create Key Pair
      description: Creates a 2048-bit RSA key pair with the specified name.
      operationId: createkeypair
      x-api-path-slug: actioncreatekeypair-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: KeyName
        description: The name of the key pair
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key Pair
  /?Action=CreateNatGateway:
    get:
      summary: Create Nat Gateway
      description: Creates a NAT gateway in the specified subnet.
      operationId: createnatgateway
      x-api-path-slug: actioncreatenatgateway-get
      parameters:
      - in: query
        name: NatGatewayId
        description: The ID of the NAT gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gateway
  /?Action=CreateNetworkAcl:
    get:
      summary: Create Network Acl
      description: Creates a network ACL in a VPC.
      operationId: createnetworkacl
      x-api-path-slug: actioncreatenetworkacl-get
      parameters:
      - in: query
        name: CidrBlock
        description: The IPv4 network range to allow or deny, in CIDR notation (for
          example                172
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Egress
        description: Indicates whether this is an egress rule (rule is applied to
          traffic leaving the subnet)
        type: string
      - in: query
        name: Icmp
        description: 'ICMP protocol: The ICMP or ICMPv6 type and code'
        type: string
      - in: query
        name: Ipv6CidrBlock
        description: The IPv6 network range to allow or deny, in CIDR notation (for
          example                2001:db8:1234:1a00::/64)
        type: string
      - in: query
        name: NetworkAclId
        description: The ID of the network ACL
        type: string
      - in: query
        name: PortRange
        description: 'TCP or UDP protocols: The range of ports the rule applies to'
        type: string
      - in: query
        name: Protocol
        description: The protocol
        type: string
      - in: query
        name: RuleAction
        description: Indicates whether to allow or deny the traffic that matches the
          rule
        type: string
      - in: query
        name: RuleNumber
        description: The rule number for the entry (for example, 100)
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC ACL
  /?Action=CreateNetworkAclEntry:
    get:
      summary: Create Network Acl Entry
      description: Creates an entry (a rule) in a network ACL with the specified rule
        number.
      operationId: createnetworkaclentry
      x-api-path-slug: actioncreatenetworkaclentry-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: NetworkAclId
        description: The ID of the network ACL
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC ACL
  /?Action=CreateNetworkInterface:
    get:
      summary: Create Network Interface
      description: Creates a network interface in the specified subnet.
      operationId: createnetworkinterface
      x-api-path-slug: actioncreatenetworkinterface-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of the network interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=CreatePlacementGroup:
    get:
      summary: Create Placement Group
      description: Creates a placement group that you launch cluster instances into.
      operationId: createplacementgroup
      x-api-path-slug: actioncreateplacementgroup-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: GroupName
        description: The name of the placement group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Group
  /?Action=CreateReservedInstancesListing:
    get:
      summary: Create Reserved Instances Listing
      description: "Creates a listing for Amazon EC2 Standard Reserved Instances to
        be sold in the Reserved Instance\n\t\t\tMarketplace."
      operationId: createreservedinstanceslisting
      x-api-path-slug: actioncreatereservedinstanceslisting-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: OfferingClass
        description: Describes whether the Reserved Instance is Standard or Convertible
        type: string
      - in: query
        name: OfferingType
        description: The Reserved Instance offering type
        type: string
      - in: query
        name: ReservedInstancesId.N
        description: One or more Reserved Instance IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instance
  /?Action=CreateRoute:
    get:
      summary: Create Route
      description: Creates a route in a route table within a VPC.
      operationId: createroute
      x-api-path-slug: actioncreateroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=CreateRouteTable:
    get:
      summary: Create Route Table
      description: Creates a route table for the specified VPC.
      operationId: createroutetable
      x-api-path-slug: actioncreateroutetable-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The IPv4 CIDR range for the route
        type: string
      - in: query
        name: DestinationIpv6CidrBlock
        description: The IPv6 CIDR range for the route
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=CreateSecurityGroup:
    get:
      summary: Create Security Group
      description: Creates a security group.
      operationId: createsecuritygroup
      x-api-path-slug: actioncreatesecuritygroup-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: GroupName
        description: '[EC2-Classic, default VPC] The name of the security group'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=CreateSnapshot:
    get:
      summary: Create Snapshot
      description: Creates a snapshot of an EBS volume and stores it in Amazon S3.
      operationId: createsnapshot
      x-api-path-slug: actioncreatesnapshot-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone in which to create the volume
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Encrypted
        description: Specifies whether the volume should be encrypted
        type: string
      - in: query
        name: Iops
        description: Only valid for Provisioned IOPS SSD volumes
        type: string
      - in: query
        name: KmsKeyId
        description: The full ARN of the AWS Key Management Service (AWS KMS) customer
          master key (CMK) to use when creating the encrypted      volume
        type: string
      - in: query
        name: Size
        description: The size of the volume, in GiBs
        type: string
      - in: query
        name: SnapshotId
        description: The snapshot from which to create the volume
        type: string
      - in: query
        name: VolumeType
        description: The volume type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshot
  /?Action=CreateSpotDatafeedSubscription:
    get:
      summary: Create Spot Datafeed Subscription
      description: Creates a data feed for Spot instances, enabling you to view Spot
        instance usage logs.
      operationId: createspotdatafeedsubscription
      x-api-path-slug: actioncreatespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet
  /?Action=CreateSubnet:
    get:
      summary: Create Subnet
      description: Creates a subnet in an existing VPC.
      operationId: createsubnet
      x-api-path-slug: actioncreatesubnet-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: SubnetId
        description: The ID of the subnet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet
  /?Action=CreateTags:
    get:
      summary: Create Tags
      description: |-
        Adds or overwrites one or more tags for the specified Amazon EC2 resource or
                 resources.
      operationId: createtags
      x-api-path-slug: actioncreatetags-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ResourceId.N
        description: The ID of the resource
        type: string
      - in: query
        name: Tag.N
        description: One or more tags to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=CreateVolume:
    get:
      summary: Create Volume
      description: Creates an EBS volume that can be attached to an instance in the
        same Availability Zone.
      operationId: createvolume
      x-api-path-slug: actioncreatevolume-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: SnapshotId
        description: The ID of the EBS snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volume
  /?Action=CreateVpc:
    get:
      summary: Create Vpc
      description: Creates a VPC with the specified IPv4 CIDR block.
      operationId: createvpc
      x-api-path-slug: actioncreatevpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=CreateVpcEndpoint:
    get:
      summary: Create Vpc Endpoint
      description: Creates a VPC endpoint for a specified AWS service.
      operationId: createvpcendpoint
      x-api-path-slug: actioncreatevpcendpoint-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcEndpointId.N
        description: One or more endpoint IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint
  /?Action=CreateVpcPeeringConnection:
    get:
      summary: Create Vpc Peering Connection
      description: 'Requests a VPC peering connection between two VPCs: a requester
        VPC that you own and a peer VPC with which to create the connection.'
      operationId: createvpcpeeringconnection
      x-api-path-slug: actioncreatevpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=CreateVpnConnection:
    get:
      summary: Create Vpn Connection
      description: |-
        Creates a VPN connection between an existing virtual private gateway and a VPN customer
                    gateway.
      operationId: createvpnconnection
      x-api-path-slug: actioncreatevpnconnection-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The CIDR block associated with the local subnet of the customer
          network
        type: string
      - in: query
        name: VpnConnectionId
        description: The ID of the VPN connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Connection
  /?Action=CreateVpnConnectionRoute:
    get:
      summary: Create Vpn Connection Route
      description: Creates a static route associated with a VPN connection between
        an existing virtual private gateway and a VPN customer gateway.
      operationId: createvpnconnectionroute
      x-api-path-slug: actioncreatevpnconnectionroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpnConnectionId
        description: The ID of the VPN connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Connection Route
  /?Action=CreateVpnGateway:
    get:
      summary: Create Vpn Gateway
      description: Creates a virtual private gateway.
      operationId: createvpngateway
      x-api-path-slug: actioncreatevpngateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
  /?Action=DeleteCustomerGateway:
    get:
      summary: Delete Customer Gateway
      description: Deletes the specified customer gateway.
      operationId: deletecustomergateway
      x-api-path-slug: actiondeletecustomergateway-get
      parameters:
      - in: query
        name: CustomerGatewayId.N
        description: One or more customer gateway IDs
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Customer Gateway
  /?Action=DeleteDhcpOptions:
    get:
      summary: Delete Dhcp Options
      description: Deletes the specified set of DHCP options.
      operationId: deletedhcpoptions
      x-api-path-slug: actiondeletedhcpoptions-get
      parameters:
      - in: query
        name: DhcpOptionsId.N
        description: The IDs of one or more DHCP options sets
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=DeleteEgressOnlyInternetGateway:
    get:
      summary: Delete Egress Only Internet Gateway
      description: Deletes an egress-only Internet gateway.
      operationId: deleteegressonlyinternetgateway
      x-api-path-slug: actiondeleteegressonlyinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InternetGatewayId
        description: The ID of the Internet gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=DeleteFlowLogs:
    get:
      summary: Delete Flow Logs
      description: Deletes one or more flow logs.
      operationId: deleteflowlogs
      x-api-path-slug: actiondeleteflowlogs-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: FlowLogId.N
        description: One or more flow log IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - FLow Logs
  /?Action=DeleteInternetGateway:
    get:
      summary: Delete Internet Gateway
      description: Deletes the specified Internet gateway.
      operationId: deleteinternetgateway
      x-api-path-slug: actiondeleteinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: EgressOnlyInternetGatewayId.N
        description: One or more egress-only Internet gateway IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=DeleteKeyPair:
    get:
      summary: Delete Key Pair
      description: Deletes the specified key pair, by removing the public key from
        Amazon EC2.
      operationId: deletekeypair
      x-api-path-slug: actiondeletekeypair-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: KeyName.N
        description: One or more key pair names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key Pair
  /?Action=DeleteNatGateway:
    get:
      summary: Delete Nat Gateway
      description: Deletes the specified NAT gateway.
      operationId: deletenatgateway
      x-api-path-slug: actiondeletenatgateway-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NatGatewayId.N
        description: One or more NAT gateway IDs
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gateway
  /?Action=DeleteNetworkAcl:
    get:
      summary: Delete Network Acl
      description: Deletes the specified network ACL.
      operationId: deletenetworkacl
      x-api-path-slug: actiondeletenetworkacl-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Egress
        description: Indicates whether the rule is an egress rule
        type: string
      - in: query
        name: NetworkAclId
        description: The ID of the network ACL
        type: string
      - in: query
        name: RuleNumber
        description: The rule number of the entry to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network ACL
  /?Action=DeleteNetworkAclEntry:
    get:
      summary: Delete Network Acl Entry
      description: Deletes the specified ingress or egress entry (rule) from the specified
        network ACL.
      operationId: deletenetworkaclentry
      x-api-path-slug: actiondeletenetworkaclentry-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: NetworkAclId.N
        description: One or more network ACL IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network ACL
  /?Action=DeleteNetworkInterface:
    get:
      summary: Delete Network Interface
      description: Deletes the specified network interface.
      operationId: deletenetworkinterface
      x-api-path-slug: actiondeletenetworkinterface-get
      parameters:
      - in: query
        name: Attribute
        description: The attribute of the network interface
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of the network interface
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=DeletePlacementGroup:
    get:
      summary: Delete Placement Group
      description: Deletes the specified placement group.
      operationId: deleteplacementgroup
      x-api-path-slug: actiondeleteplacementgroup-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: GroupName.N
        description: One or more placement group names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Group
  /?Action=DeleteRoute:
    get:
      summary: Delete Route
      description: Deletes the specified route from the specified route table.
      operationId: deleteroute
      x-api-path-slug: actiondeleteroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route
  /?Action=DeleteRouteTable:
    get:
      summary: Delete Route Table
      description: Deletes the specified route table.
      operationId: deleteroutetable
      x-api-path-slug: actiondeleteroutetable-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: RouteTableId.N
        description: One or more route table IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=DeleteSecurityGroup:
    get:
      summary: Delete Security Group
      description: Deletes a security group.
      operationId: deletesecuritygroup
      x-api-path-slug: actiondeletesecuritygroup-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request, and provides an error response
        type: string
      - in: query
        name: GroupId.N
        description: One or more security group IDs in your account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security  Group
  /?Action=DeleteSnapshot:
    get:
      summary: Delete Snapshot
      description: Deletes the specified snapshot.
      operationId: deletesnapshot
      x-api-path-slug: actiondeletesnapshot-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Snapshot
  /?Action=DeleteSpotDatafeedSubscription:
    get:
      summary: Delete Spot Datafeed Subscription
      description: Deletes the data feed for Spot instances.
      operationId: deletespotdatafeedsubscription
      x-api-path-slug: actiondeletespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Data Feed Subscription
  /?Action=DeleteSubnet:
    get:
      summary: Delete Subnet
      description: Deletes the specified subnet.
      operationId: deletesubnet
      x-api-path-slug: actiondeletesubnet-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: SubnetId.N
        description: One or more subnet IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet
  /?Action=DeleteTags:
    get:
      summary: Delete Tags
      description: Deletes the specified set of tags from the specified set of resources.
      operationId: deletetags
      x-api-path-slug: actiondeletetags-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DeleteVolume:
    get:
      summary: Delete Volume
      description: Deletes the specified EBS volume.
      operationId: deletevolume
      x-api-path-slug: actiondeletevolume-get
      parameters:
      - in: query
        name: Attribute
        description: The snapshot attribute you would like to view
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: SnapshotId
        description: The ID of the EBS snapshot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volume
  /?Action=DeleteVpc:
    get:
      summary: Delete Vpc
      description: Deletes the specified VPC.
      operationId: deletevpc
      x-api-path-slug: actiondeletevpc-get
      parameters:
      - in: query
        name: Attribute
        description: The VPC attribute
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DeleteVpcEndpoints:
    get:
      summary: Delete Vpc Endpoints
      description: Deletes one or more specified VPC endpoints.
      operationId: deletevpcendpoints
      x-api-path-slug: actiondeletevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: PrefixListId.N
        description: One or more prefix list IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
  /?Action=DeleteVpcPeeringConnection:
    get:
      summary: Delete Vpc Peering Connection
      description: Deletes a VPC peering connection.
      operationId: deletevpcpeeringconnection
      x-api-path-slug: actiondeletevpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcPeeringConnectionId.N
        description: One or more VPC peering connection IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=DeleteVpnConnection:
    get:
      summary: Delete Vpn Connection
      description: Deletes the specified VPN connection.
      operationId: deletevpnconnection
      x-api-path-slug: actiondeletevpnconnection-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The CIDR block associated with the local subnet of the customer
          network
        type: string
      - in: query
        name: VpnConnectionId
        description: The ID of the VPN connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connection
  /?Action=DeleteVpnConnectionRoute:
    get:
      summary: Delete Vpn Connection Route
      description: Deletes the specified static route associated with a VPN connection
        between an existing virtual private gateway and a VPN customer gateway.
      operationId: deletevpnconnectionroute
      x-api-path-slug: actiondeletevpnconnectionroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpnConnectionId.N
        description: One or more VPN connection IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connection Route
  /?Action=DeleteVpnGateway:
    get:
      summary: Delete Vpn Gateway
      description: Deletes the specified virtual private gateway.
      operationId: deletevpngateway
      x-api-path-slug: actiondeletevpngateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpnGatewayId.N
        description: One or more virtual private gateway IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
  /?Action=DeregisterImage:
    get:
      summary: Deregister Image
      description: Deregisters the specified AMI.
      operationId: deregisterimage
      x-api-path-slug: actionderegisterimage-get
      parameters:
      - in: query
        name: Attribute
        description: The AMI attribute
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ImageId
        description: The ID of the AMI
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=DescribeAccountAttributes:
    get:
      summary: Describe Account Attributes
      description: Describes attributes of your AWS account.
      operationId: describeaccountattributes
      x-api-path-slug: actiondescribeaccountattributes-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensureidempotency
          of the request
        type: string
      - in: query
        name: Description
        description: A description for the new AMI in the destination region
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Encrypted
        description: Specifies whether the destination snapshots of the copied image
          should be encrypted
        type: string
      - in: query
        name: KmsKeyId
        description: The full ARN of the AWS Key Management Service (AWS KMS) CMK
          to use when encrypting the snapshots of an image during a copy operation
        type: string
      - in: query
        name: Name
        description: The name of the new AMI in the destination region
        type: string
      - in: query
        name: SourceImageId
        description: The ID of the AMI to copy
        type: string
      - in: query
        name: SourceRegion
        description: The name of the region that contains the AMI to copy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account
  /?Action=DescribeAddresses:
    get:
      summary: Describe Addresses
      description: Describes one or more of your Elastic IP addresses.
      operationId: describeaddresses
      x-api-path-slug: actiondescribeaddresses-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: PublicIp.N
        description: One or more Elastic IP addresses
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP ADdress
  /?Action=DescribeAvailabilityZones:
    get:
      summary: Describe Availability Zones
      description: Describes one or more of the Availability Zones that are available
        to you.
      operationId: describeavailabilityzones
      x-api-path-slug: actiondescribeavailabilityzones-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: RegionName.N
        description: The names of one or more regions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Availability Zones
  /?Action=DescribeBundleTasks:
    get:
      summary: Describe Bundle Tasks
      description: Describes one or more of your bundling tasks.
      operationId: describebundletasks
      x-api-path-slug: actiondescribebundletasks-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of an EC2-Classic instance to link to the ClassicLink-enabled
          VPC
        type: string
      - in: query
        name: SecurityGroupId.N
        description: The ID of one or more of the VPCs security groups
        type: string
      - in: query
        name: VpcId
        description: The ID of a ClassicLink-enabled VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Task
  /?Action=DescribeClassicLinkInstances:
    get:
      summary: Describe Classic Link Instances
      description: Describes one or more of your linked EC2-Classic instances.
      operationId: describeclassiclinkinstances
      x-api-path-slug: actiondescribeclassiclinkinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcId.N
        description: One or more VPCs for which you want to describe the ClassicLink
          status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeConversionTasks:
    get:
      summary: Describe Conversion Tasks
      description: Describes one or more of your conversion tasks.
      operationId: describeconversiontasks
      x-api-path-slug: actiondescribeconversiontasks-get
      responses:
        200:
          description: OK
      tags:
      - Version Tasks
  /?Action=DescribeCustomerGateways:
    get:
      summary: Describe Customer Gateways
      description: Describes one or more of your VPN customer gateways.
      operationId: describecustomergateways
      x-api-path-slug: actiondescribecustomergateways-get
      parameters:
      - in: query
        name: AutoPlacement
        description: This is enabled by default
        type: string
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the Dedicated Hosts
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of the request
        type: string
      - in: query
        name: InstanceType
        description: Specify the instance type that you want your Dedicated Hosts
          to be configured for
        type: string
      - in: query
        name: Quantity
        description: The number of Dedicated Hosts you want to allocate to your account
          with these            parameters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Customer Gateways
  /?Action=DescribeDhcpOptions:
    get:
      summary: Describe Dhcp Options
      description: Describes one or more of your DHCP options sets.
      operationId: describedhcpoptions
      x-api-path-slug: actiondescribedhcpoptions-get
      parameters:
      - in: query
        name: Device
        description: The device name to expose to the instance (for example, /dev/sdh
          or        xvdh)
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: VolumeId
        description: The ID of the EBS volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=DescribeEgressOnlyInternetGateways:
    get:
      summary: Describe Egress Only Internet Gateways
      description: Describes one or more of your egress-only Internet gateways.
      operationId: describeegressonlyinternetgateways
      x-api-path-slug: actiondescribeegressonlyinternetgateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InternetGatewayId.N
        description: One or more Internet gateway IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=DescribeExportTasks:
    get:
      summary: Describe Export Tasks
      description: Describes one or more of your export tasks.
      operationId: describeexporttasks
      x-api-path-slug: actiondescribeexporttasks-get
      parameters:
      - in: query
        name: AmazonProvidedIpv6CidrBlock
        description: Requests an Amazon-provided IPv6 CIDR block with a /56 prefix
          length for the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Export Takss
  /?Action=DescribeFlowLogs:
    get:
      summary: Describe Flow Logs
      description: Describes one or more flow logs.
      operationId: describeflowlogs
      x-api-path-slug: actiondescribeflowlogs-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy to attach to the endpoint that controls access to the
          service
        type: string
      - in: query
        name: RouteTableId.N
        description: One or more route table IDs
        type: string
      - in: query
        name: ServiceName
        description: The AWS service name, in the form com
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC in which the endpoint will be used
        type: string
      responses:
        200:
          description: OK
      tags:
      - Flow Logs
  /?Action=DescribeHostReservationOfferings:
    get:
      summary: Describe Host Reservation Offerings
      description: Describes the Dedicated Host Reservations that are available to
        purchase.
      operationId: describehostreservationofferings
      x-api-path-slug: actiondescribehostreservationofferings-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: HostReservationIdSet.N
        description: One or more host reservation IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=DescribeHostReservations:
    get:
      summary: Describe Host Reservations
      description: |-
        Describes Dedicated Host Reservations which are associated with Dedicated Hosts in
                    your account.
      operationId: describehostreservations
      x-api-path-slug: actiondescribehostreservations-get
      parameters:
      - in: query
        name: HostIdSet.N
        description: The ID/s of the Dedicated Host/s that the reservation will be
          associated            with
        type: string
      - in: query
        name: OfferingId
        description: The offering ID of the reservation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=DescribeHosts:
    get:
      summary: Describe Hosts
      description: Describes one or more of your Dedicated Hosts.
      operationId: describehosts
      x-api-path-slug: actiondescribehosts-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxDuration
        description: This is the maximum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: This is the minimum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: OfferingId
        description: The ID of the reservation offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Hosts
  /?Action=DescribeIdentityIdFormat:
    get:
      summary: Describe Identity Id Format
      description: |-
        Describes the ID format settings for resources for the specified IAM user, IAM role, or root
              user.
      operationId: describeidentityidformat
      x-api-path-slug: actiondescribeidentityidformat-get
      parameters:
      - in: query
        name: Resource
        description: 'The type of resource: instance | reservation |        snapshot
          | volume'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Format
  /?Action=DescribeIdFormat:
    get:
      summary: Describe Id Format
      description: Describes the ID format settings for your resources on a per-region
        basis, for example, to view which resource types are enabled for longer IDs.
      operationId: describeidformat
      x-api-path-slug: actiondescribeidformat-get
      parameters:
      - in: query
        name: PrincipalArn
        description: The ARN of the principal, which can be an IAM user, IAM role,
          or the root user
        type: string
      - in: query
        name: Resource
        description: 'The type of resource: instance | reservation |        snapshot
          | volume'
        type: string
      - in: query
        name: UseLongIds
        description: Indicates whether the resource should use longer IDs (17-character
          IDs)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Format
  /?Action=DescribeImageAttribute:
    get:
      summary: Describe Image Attribute
      description: Describes the specified attribute of the specified AMI.
      operationId: describeimageattribute
      x-api-path-slug: actiondescribeimageattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ExecutableBy.N
        description: Scopes the images by users with explicit launch permissions
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ImageId.N
        description: One or more image IDs
        type: string
      - in: query
        name: Owner.N
        description: Filters the images by the owner
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=DescribeImages:
    get:
      summary: Describe Images
      description: Describes one or more of the images (AMIs, AKIs, and ARIs) available
        to you.
      operationId: describeimages
      x-api-path-slug: actiondescribeimages-get
      parameters:
      - in: query
        name: Attribute
        description: The name of the attribute to modify
        type: string
      - in: query
        name: Description
        description: A description for the AMI
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ImageId
        description: The ID of the AMI
        type: string
      - in: query
        name: LaunchPermission
        description: A launch permission modification
        type: string
      - in: query
        name: OperationType
        description: The operation type
        type: string
      - in: query
        name: ProductCode.N
        description: One or more product codes
        type: string
      - in: query
        name: UserGroup.N
        description: One or more user groups
        type: string
      - in: query
        name: UserId.N
        description: One or more AWS account IDs
        type: string
      - in: query
        name: Value
        description: The value of the attribute being modified
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=DescribeImportImageTasks:
    get:
      summary: Describe Import Image Tasks
      description: Displays details about an import virtual machine or import snapshot
        tasks that are already created.
      operationId: describeimportimagetasks
      x-api-path-slug: actiondescribeimportimagetasks-get
      responses:
        200:
          description: OK
      tags:
      - Import Image Tasks
  /?Action=DescribeImportSnapshotTasks:
    get:
      summary: Describe Import Snapshot Tasks
      description: Describes your import snapshot tasks.
      operationId: describeimportsnapshottasks
      x-api-path-slug: actiondescribeimportsnapshottasks-get
      parameters:
      - in: query
        name: Description
        description: A description for the instance being imported
        type: string
      - in: query
        name: DiskImage.N
        description: The disk image
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,      and provides an error response
        type: string
      - in: query
        name: LaunchSpecification
        description: The launch specification
        type: string
      - in: query
        name: Platform
        description: The instance operating system
        type: string
      responses:
        200:
          description: OK
      tags:
      - Import Snapshot Takss
  /?Action=DescribeInstanceAttribute:
    get:
      summary: Describe Instance Attribute
      description: Describes the specified attribute of the specified instance.
      operationId: describeinstanceattribute
      x-api-path-slug: actiondescribeinstanceattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token to request the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeInstances:
    get:
      summary: Describe Instances
      description: Describes one or more of your instances.
      operationId: describeinstances
      x-api-path-slug: actiondescribeinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: IncludeAllInstances
        description: When true, includes the health status for all instances
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeInstanceStatus:
    get:
      summary: Describe Instance Status
      description: Describes the status of one or more instances.
      operationId: describeinstancestatus
      x-api-path-slug: actiondescribeinstancestatus-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance Status
  /?Action=DescribeInternetGateways:
    get:
      summary: Describe Internet Gateways
      description: Describes one or more of your Internet gateways.
      operationId: describeinternetgateways
      x-api-path-slug: actiondescribeinternetgateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InternetGatewayId
        description: The ID of the Internet gateway
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateways
  /?Action=DescribeKeyPairs:
    get:
      summary: Describe Key Pairs
      description: Describes one or more of your key pairs.
      operationId: describekeypairs
      x-api-path-slug: actiondescribekeypairs-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: KeyName
        description: A unique name for the key pair
        type: string
      - in: query
        name: PublicKeyMaterial
        description: The public key
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key Paris
  /?Action=DescribeMovingAddresses:
    get:
      summary: Describe Moving Addresses
      description: Describes your Elastic IP addresses that are being moved to the
        EC2-VPC platform, or that are being restored to the EC2-Classic platform.
      operationId: describemovingaddresses
      x-api-path-slug: actiondescribemovingaddresses-get
      parameters:
      - in: query
        name: AssociationId
        description: '[EC2-VPC] The association ID'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: PublicIp
        description: '[EC2-Classic] The Elastic IP address'
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=DescribeNatGateways:
    get:
      summary: Describe Nat Gateways
      description: Describes one or more of the your NAT gateways.
      operationId: describenatgateways
      x-api-path-slug: actiondescribenatgateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - NAT Gateways
  /?Action=DescribeNetworkAcls:
    get:
      summary: Describe Network Acls
      description: Describes one or more of your network ACLs.
      operationId: describenetworkacls
      x-api-path-slug: actiondescribenetworkacls-get
      parameters:
      - in: query
        name: AssociationId
        description: The ID of the current association between the original network
          ACL and the subnet
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: NetworkAclId
        description: The ID of the new network ACL to associate with the subnet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network ACL
  /?Action=DescribeNetworkInterfaceAttribute:
    get:
      summary: Describe Network Interface Attribute
      description: Describes a network interface attribute.
      operationId: describenetworkinterfaceattribute
      x-api-path-slug: actiondescribenetworkinterfaceattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: NetworkInterfaceId.N
        description: One or more network interface IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=DescribeNetworkInterfaces:
    get:
      summary: Describe Network Interfaces
      description: Describes one or more of your network interfaces.
      operationId: describenetworkinterfaces
      x-api-path-slug: actiondescribenetworkinterfaces-get
      parameters:
      - in: query
        name: AttachmentId
        description: The ID of the attachment
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Force
        description: Specifies whether to force a detachment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=DescribePlacementGroups:
    get:
      summary: Describe Placement Groups
      description: Describes one or more of your placement groups.
      operationId: describeplacementgroups
      x-api-path-slug: actiondescribeplacementgroups-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ZoneName.N
        description: The names of one or more Availability Zones
        type: string
      responses:
        200:
          description: OK
      tags:
      - Placement Groups
  /?Action=DescribePrefixLists:
    get:
      summary: Describe Prefix Lists
      description: Describes available AWS services in a prefix list format, which
        includes the prefix list name and prefix list ID of the service and the IP
        address range for the service.
      operationId: describeprefixlists
      x-api-path-slug: actiondescribeprefixlists-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcEndpointId.N
        description: One or more endpoint IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prefix List
  /?Action=DescribeRegions:
    get:
      summary: Describe Regions
      description: Describes one or more regions that are currently available to you.
      operationId: describeregions
      x-api-path-slug: actiondescriberegions-get
      responses:
        200:
          description: OK
      tags:
      - Regions
  /?Action=DescribeReservedInstances:
    get:
      summary: Describe Reserved Instances
      description: Describes one or more of the Reserved Instances that you purchased.
      operationId: describereservedinstances
      x-api-path-slug: actiondescribereservedinstances-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ReservedInstancesId
        description: One or more Reserved Instance IDs
        type: string
      - in: query
        name: ReservedInstancesListingId
        description: One or more Reserved Instance listing IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeReservedInstancesListings:
    get:
      summary: Describe Reserved Instances Listings
      description: Describes your account's Reserved Instance listings in the Reserved
        Instance Marketplace.
      operationId: describereservedinstanceslistings
      x-api-path-slug: actiondescribereservedinstanceslistings-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      - in: query
        name: ReservedInstancesModificationId.N
        description: IDs for the submitted modification request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeReservedInstancesModifications:
    get:
      summary: Describe Reserved Instances Modifications
      description: Describes the modifications made to your Reserved Instances.
      operationId: describereservedinstancesmodifications
      x-api-path-slug: actiondescribereservedinstancesmodifications-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone in which the Reserved Instance can be used
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: IncludeMarketplace
        description: Include Reserved Instance Marketplace offerings in the response
        type: string
      - in: query
        name: InstanceTenancy
        description: The tenancy of the instances covered by the reservation
        type: string
      - in: query
        name: InstanceType
        description: The instance type that the reservation will cover (for example,
          m1
        type: string
      - in: query
        name: MaxDuration
        description: The maximum duration (in seconds) to filter when searching for
          offerings
        type: string
      - in: query
        name: MaxInstanceCount
        description: The maximum number of instances to filter when searching for
          offerings
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: The minimum duration (in seconds) to filter when searching for
          offerings
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      - in: query
        name: OfferingClass
        description: The offering class of the Reserved Instance
        type: string
      - in: query
        name: OfferingType
        description: The Reserved Instance offering type
        type: string
      - in: query
        name: ProductDescription
        description: The Reserved Instance product platform description
        type: string
      - in: query
        name: ReservedInstancesOfferingId.N
        description: One or more Reserved Instances offering IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeReservedInstancesOfferings:
    get:
      summary: Describe Reserved Instances Offerings
      description: Describes Reserved Instance offerings that are available for purchase.
      operationId: describereservedinstancesofferings
      x-api-path-slug: actiondescribereservedinstancesofferings-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: ReservedInstanceId.N
        description: The IDs of the Convertible Reserved Instances to exchange
        type: string
      - in: query
        name: TargetConfiguration.N
        description: The configuration requirements of the Convertible Reserved Instances
          to exchange for your current      Convertible Reserved Instances
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instances
  /?Action=DescribeRouteTables:
    get:
      summary: Describe Route Tables
      description: Describes one or more of your route tables.
      operationId: describeroutetables
      x-api-path-slug: actiondescriberoutetables-get
      parameters:
      - in: query
        name: GatewayId
        description: The ID of the virtual private gateway
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Tables
  /?Action=DescribeScheduledInstanceAvailability:
    get:
      summary: Describe Scheduled Instance Availability
      description: Finds available schedules that meet the specified criteria.
      operationId: describescheduledinstanceavailability
      x-api-path-slug: actiondescribescheduledinstanceavailability-get
      responses:
        200:
          description: OK
      tags:
      - Server Instance Availability
  /?Action=DescribeScheduledInstances:
    get:
      summary: Describe Scheduled Instances
      description: Describes one or more of your Scheduled Instances.
      operationId: describescheduledinstances
      x-api-path-slug: actiondescribescheduledinstances-get
      responses:
        200:
          description: OK
      tags:
      - Scheduled Server Instances
  /?Action=DescribeSecurityGroupReferences (EC2-VPC only):
    get:
      summary: Describe Security Group References ( E C2- V P C only)
      description: '[EC2-VPC only] Describes the VPCs on the other side of a VPC peering
        connection that are referencing the security groups you''ve specified in this
        request.'
      operationId: describesecuritygroupreferences-ec2vpc-only
      x-api-path-slug: actiondescribesecuritygroupreferences-ec2vpc-only-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: GroupId.N
        description: One or more security group IDs
        type: string
      - in: query
        name: GroupName.N
        description: '[EC2-Classic and default VPC only] One or more security group
          names'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=DescribeSecurityGroups:
    get:
      summary: Describe Security Groups
      description: Describes one or more of your security groups.
      operationId: describesecuritygroups
      x-api-path-slug: actiondescribesecuritygroups-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request, and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=DescribeSnapshotAttribute:
    get:
      summary: Describe Snapshot Attribute
      description: Describes the specified attribute of the specified snapshot.
      operationId: describesnapshotattribute
      x-api-path-slug: actiondescribesnapshotattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of snapshot results returned by DescribeSnapshots
          in      paginated output
        type: string
      - in: query
        name: NextToken
        description: The NextToken value returned from a previous paginated        DescribeSnapshots
          request where MaxResults was used and the      results exceeded the value
          of that parameter
        type: string
      - in: query
        name: Owner.N
        description: Returns the snapshots owned by the specified owner
        type: string
      - in: query
        name: RestorableBy.N
        description: One or more AWS accounts IDs that can create volumes from the
          snapshot
        type: string
      - in: query
        name: SnapshotId.N
        description: One or more snapshot IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive Snapshot
  /?Action=DescribeSnapshots:
    get:
      summary: Describe Snapshots
      description: Describes one or more of the EBS snapshots available to you.
      operationId: describesnapshots
      x-api-path-slug: actiondescribesnapshots-get
      parameters:
      - in: query
        name: Attribute
        description: The instance attribute
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Drive Snapshot
  /?Action=DescribeSpotDatafeedSubscription:
    get:
      summary: Describe Spot Datafeed Subscription
      description: Describes the data feed for Spot instances.
      operationId: describespotdatafeedsubscription
      x-api-path-slug: actiondescribespotdatafeedsubscription-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: SpotInstanceRequestId.N
        description: One or more Spot instance request IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Data Feed
  /?Action=DescribeSpotFleetInstances:
    get:
      summary: Describe Spot Fleet Instances
      description: Describes the running instances for the specified Spot fleet.
      operationId: describespotfleetinstances
      x-api-path-slug: actiondescribespotfleetinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: EventType
        description: The type of events to describe
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: SpotFleetRequestId
        description: The ID of the Spot fleet request
        type: string
      - in: query
        name: StartTime
        description: The starting date and time for the events, in UTC format (for
          example, YYYY-MM-DDTHH:MM:SSZ)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Fleet Instance
  /?Action=DescribeSpotFleetRequestHistory:
    get:
      summary: Describe Spot Fleet Request History
      description: Describes the events for the specified Spot fleet request during
        the specified time.
      operationId: describespotfleetrequesthistory
      x-api-path-slug: actiondescribespotfleetrequesthistory-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: SpotFleetRequestId.N
        description: The IDs of the Spot fleet requests
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Fleet Request History
  /?Action=DescribeSpotFleetRequests:
    get:
      summary: Describe Spot Fleet Requests
      description: Describes your Spot fleet requests.
      operationId: describespotfleetrequests
      x-api-path-slug: actiondescribespotfleetrequests-get
      responses:
        200:
          description: OK
      tags:
      - Sport Fleet Requests
  /?Action=DescribeSpotInstanceRequests:
    get:
      summary: Describe Spot Instance Requests
      description: Describes the Spot instance requests that belong to your account.
      operationId: describespotinstancerequests
      x-api-path-slug: actiondescribespotinstancerequests-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: Filters the results by the specified Availability Zone
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EndTime
        description: The date and time, up to the current date, from which to stop
          retrieving the price history data,        in UTC format (for example, YYYY-MM-DDTHH:MM:SSZ)
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceType.N
        description: Filters the results by the specified instance types
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: ProductDescription.N
        description: Filters the results by the specified basic product descriptions
        type: string
      - in: query
        name: StartTime
        description: The date and time, up to the past 90 days, from which to start
          retrieving the price history data,        in UTC format (for example, YYYY-MM-DDTHH:MM:SSZ)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Instance Requests
  /?Action=DescribeSpotPriceHistory:
    get:
      summary: Describe Spot Price History
      description: Describes the Spot price history.
      operationId: describespotpricehistory
      x-api-path-slug: actiondescribespotpricehistory-get
      parameters:
      - in: query
        name: AvailabilityZoneGroup
        description: The user-specified name for a logical grouping of bids
        type: string
      - in: query
        name: BlockDurationMinutes
        description: The required duration for the Spot instances (also known as Spot
          blocks), in minutes
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier that you provide to ensure
          the idempotency of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceCount
        description: The maximum number of Spot instances to launch
        type: string
      - in: query
        name: LaunchGroup
        description: The instance launch group
        type: string
      - in: query
        name: LaunchSpecification
        description: Describes the launch specification for an instance
        type: string
      - in: query
        name: SpotPrice
        description: The maximum hourly price (bid) for any Spot instance launched
          to fulfill the request
        type: string
      - in: query
        name: Type
        description: The Spot instance request type
        type: string
      - in: query
        name: ValidFrom
        description: The start date of the request
        type: string
      - in: query
        name: ValidUntil
        description: The end date of the request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Price History
  /?Action=DescribeStaleSecurityGroups (EC2-VPC only):
    get:
      summary: Describe Stale Security Groups ( E C2- V P C only)
      description: '[EC2-VPC only] Describes the stale security group rules for security
        groups in a specified VPC.'
      operationId: describestalesecuritygroups-ec2vpc-only
      x-api-path-slug: actiondescribestalesecuritygroups-ec2vpc-only-get
      parameters:
      - in: query
        name: CidrIp
        description: The CIDR IP address range
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: FromPort
        description: The start of port range for the TCP and UDP protocols, or an
          ICMP type number
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: IpPermissions.N
        description: A set of IP permissions
        type: string
      - in: query
        name: IpProtocol
        description: The IP protocol name or number
        type: string
      - in: query
        name: SourceSecurityGroupName
        description: The name of a destination security group
        type: string
      - in: query
        name: SourceSecurityGroupOwnerId
        description: The AWS account number for a destination security group
        type: string
      - in: query
        name: ToPort
        description: The end of port range for the TCP and UDP protocols, or an ICMP
          type number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=DescribeSubnets:
    get:
      summary: Describe Subnets
      description: Describes one or more of your subnets.
      operationId: describesubnets
      x-api-path-slug: actiondescribesubnets-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for the CIDR block
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnets
  /?Action=DescribeTags:
    get:
      summary: Describe Tags
      description: Describes one or more of the tags for your EC2 resources.
      operationId: describetags
      x-api-path-slug: actiondescribetags-get
      parameters:
      - in: query
        name: ConversionTaskId
        description: The ID of the conversion task
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,      and provides an error response
        type: string
      - in: query
        name: ReasonMessage
        description: The reason for canceling the conversion task
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags
  /?Action=DescribeVolumeAttribute:
    get:
      summary: Describe Volume Attribute
      description: Describes the specified attribute of the specified volume.
      operationId: describevolumeattribute
      x-api-path-slug: actiondescribevolumeattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of volume results returned by DescribeVolumes
          in paginated      output
        type: string
      - in: query
        name: NextToken
        description: The NextToken value returned from a previous paginated        DescribeVolumes
          request where MaxResults was used and the results      exceeded the value
          of that parameter
        type: string
      - in: query
        name: VolumeId.N
        description: One or more volume IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volumes
  /?Action=DescribeVolumes:
    get:
      summary: Describe Volumes
      description: Describes the specified EBS volumes.
      operationId: describevolumes
      x-api-path-slug: actiondescribevolumes-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of volume results returned by DescribeVolumeStatus
          in      paginated output
        type: string
      - in: query
        name: NextToken
        description: The NextToken value to include in a future DescribeVolumeStatus      request
        type: string
      - in: query
        name: VolumeId.N
        description: One or more volume IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volumes
  /?Action=DescribeVolumeStatus:
    get:
      summary: Describe Volume Status
      description: Describes the status of the specified volumes.
      operationId: describevolumestatus
      x-api-path-slug: actiondescribevolumestatus-get
      parameters:
      - in: query
        name: Device
        description: The device name
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: Force
        description: Forces detachment if the previous detachment attempt did not
          occur cleanly (for example,      logging into an instance, unmounting the
          volume, and detaching normally)
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volume Status
  /?Action=DescribeVpcAttribute:
    get:
      summary: Describe Vpc Attribute
      description: Describes the specified attribute of the specified VPC.
      operationId: describevpcattribute
      x-api-path-slug: actiondescribevpcattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcId.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcClassicLink:
    get:
      summary: Describe Vpc Classic Link
      description: Describes the ClassicLink status of one or more VPCs.
      operationId: describevpcclassiclink
      x-api-path-slug: actiondescribevpcclassiclink-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcIds.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcClassicLinkDnsSupport:
    get:
      summary: Describe Vpc Classic Link Dns Support
      description: Describes the ClassicLink DNS support status of one or more VPCs.
      operationId: describevpcclassiclinkdnssupport
      x-api-path-slug: actiondescribevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to unlink from the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC to which the instance is linked
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
  /?Action=DescribeVpcEndpoints:
    get:
      summary: Describe Vpc Endpoints
      description: Describes one or more of your VPC endpoints.
      operationId: describevpcendpoints
      x-api-path-slug: actiondescribevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
  /?Action=DescribeVpcEndpointServices:
    get:
      summary: Describe Vpc Endpoint Services
      description: Describes all supported AWS services that can be specified when
        creating a VPC endpoint.
      operationId: describevpcendpointservices
      x-api-path-slug: actiondescribevpcendpointservices-get
      parameters:
      - in: query
        name: AddRouteTableId.N
        description: One or more route tables IDs to associate with the endpoint
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy document to attach to the endpoint
        type: string
      - in: query
        name: RemoveRouteTableId.N
        description: One or more route table IDs to disassociate from the endpoint
        type: string
      - in: query
        name: ResetPolicy
        description: Specify true to reset the policy document to the default policy
        type: string
      - in: query
        name: VpcEndpointId
        description: The ID of the endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint Services
  /?Action=DescribeVpcPeeringConnections:
    get:
      summary: Describe Vpc Peering Connections
      description: Describes one or more of your VPC peering connections.
      operationId: describevpcpeeringconnections
      x-api-path-slug: actiondescribevpcpeeringconnections-get
      parameters:
      - in: query
        name: AccepterPeeringConnectionOptions
        description: The VPC peering connection options for the accepter VPC
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: RequesterPeeringConnectionOptions
        description: The VPC peering connection options for the requester VPC
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connections
  /?Action=DescribeVpcs:
    get:
      summary: Describe Vpcs
      description: Describes one or more of your VPCs.
      operationId: describevpcs
      x-api-path-slug: actiondescribevpcs-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for the CIDR block
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpnConnections:
    get:
      summary: Describe Vpn Connections
      description: Describes one or more of your VPN connections.
      operationId: describevpnconnections
      x-api-path-slug: actiondescribevpnconnections-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Connections
  /?Action=DescribeVpnGateways:
    get:
      summary: Describe Vpn Gateways
      description: Describes one or more of your virtual private gateways.
      operationId: describevpngateways
      x-api-path-slug: actiondescribevpngateways-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateways
  /?Action=DetachClassicLinkVpc:
    get:
      summary: Detach Classic Link Vpc
      description: Unlinks (detaches) a linked EC2-Classic instance from a VPC.
      operationId: detachclassiclinkvpc
      x-api-path-slug: actiondetachclassiclinkvpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DetachInternetGateway:
    get:
      summary: Detach Internet Gateway
      description: Detaches an Internet gateway from a VPC, disabling connectivity
        between the Internet and the VPC.
      operationId: detachinternetgateway
      x-api-path-slug: actiondetachinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: KeyName
        description: A unique name for the key pair
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=DetachNetworkInterface:
    get:
      summary: Detach Network Interface
      description: Detaches a network interface from an instance.
      operationId: detachnetworkinterface
      x-api-path-slug: actiondetachnetworkinterface-get
      parameters:
      - in: query
        name: Attachment
        description: Information about the interface attachment
        type: string
      - in: query
        name: Description
        description: A description for the network interface
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of the network interface
        type: string
      - in: query
        name: SecurityGroupId.N
        description: Changes the security groups for the network interface
        type: string
      - in: query
        name: SourceDestCheck
        description: Indicates whether source/destination checking is enabled
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network Interface
  /?Action=DetachVolume:
    get:
      summary: Detach Volume
      description: Detaches an EBS volume from an instance.
      operationId: detachvolume
      x-api-path-slug: actiondetachvolume-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: VolumeId
        description: The ID of the volume
        type: string
      responses:
        200:
          description: OK
      tags:
      - Volume
  /?Action=DisableVgwRoutePropagation:
    get:
      summary: Disable Vgw Route Propagation
      description: Disables a virtual private gateway (VGW) from propagating routes
        to a specified route table of a VPC.
      operationId: disablevgwroutepropagation
      x-api-path-slug: actiondisablevgwroutepropagation-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID representing the current association between
          the route table and subnet
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual Private Gateway
  /?Action=DisableVpcClassicLink:
    get:
      summary: Disable Vpc Classic Link
      description: Disables ClassicLink for a VPC.
      operationId: disablevpcclassiclink
      x-api-path-slug: actiondisablevpcclassiclink-get
      parameters:
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DisableVpcClassicLinkDnsSupport:
    get:
      summary: Disable Vpc Classic Link Dns Support
      description: Disables ClassicLink DNS support for a VPC.
      operationId: disablevpcclassiclinkdnssupport
      x-api-path-slug: actiondisablevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
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