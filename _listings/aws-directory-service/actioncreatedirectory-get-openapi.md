---
swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 0
info:
  title: AWS Directory Service API Create Directory
  version: 1.0.0
  description: Creates a Simple AD directory.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddIpRoutes:
    get:
      summary: Add Ip Routes
      description: If the DNS server for your on-premises domain uses a publicly addressable
        IP address, you must add a CIDR address block to correctly route traffic to
        and from your Microsoft AD on Amazon Web Services.
      operationId: addIpRoutes
      x-api-path-slug: actionaddiproutes-get
      parameters:
      - in: query
        name: DirectoryId
        description: Identifier (ID) of the directory to which to add the address
          block
        type: string
      - in: query
        name: IpRoutes
        description: IP address blocks, using CIDR format, of the traffic to route
        type: string
      - in: query
        name: UpdateSecurityGroupForDirectoryControllers
        description: 'If set to true, updates the inbound and outbound rules of the
          security group that has the description: AWS created security group for
          directory ID directory controllers'
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address Routes
  /?Action=AddTagsToResource:
    get:
      summary: Add Tags To Resource
      description: Adds or overwrites one or more tags for the specified directory.
      operationId: addTagsToResource
      x-api-path-slug: actionaddtagstoresource-get
      parameters:
      - in: query
        name: ResourceId
        description: Identifier (ID) for the directory to which to add the tag
        type: string
      - in: query
        name: Tags
        description: The tags to be assigned to the directory
        type: string
      responses:
        200:
          description: OK
      tags:
      - Resource Tags
  /?Action=CancelSchemaExtension:
    get:
      summary: Cancel Schema Extension
      description: Cancels an in-progress schema extension to a Microsoft AD directory.
      operationId: cancelSchemaExtension
      x-api-path-slug: actioncancelschemaextension-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory whose schema extension will be
          canceled
        type: string
      - in: query
        name: SchemaExtensionId
        description: The identifier of the schema extension that will be canceled
        type: string
      responses:
        200:
          description: OK
      tags:
      - Schemas
  /?Action=ConnectDirectory:
    get:
      summary: Connect Directory
      description: Creates an AD Connector to connect to an on-premises directory.
      operationId: connectDirectory
      x-api-path-slug: actionconnectdirectory-get
      parameters:
      - in: query
        name: ConnectSettings
        description: A DirectoryConnectSettings object that contains additional information
          for the         operation
        type: string
      - in: query
        name: Description
        description: A textual description for the directory
        type: string
      - in: query
        name: Name
        description: The fully-qualified name of the on-premises directory, such as            corp
        type: string
      - in: query
        name: Password
        description: The password for the on-premises user account
        type: string
      - in: query
        name: ShortName
        description: The NetBIOS name of the on-premises directory, such as CORP
        type: string
      - in: query
        name: Size
        description: The size of the directory
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
  /?Action=CreateAlias:
    get:
      summary: Create Alias
      description: Creates an alias for a directory and assigns the alias to the directory.
      operationId: createAlias
      x-api-path-slug: actioncreatealias-get
      parameters:
      - in: query
        name: Alias
        description: The requested alias
        type: string
      - in: query
        name: DirectoryId
        description: The identifier of the directory for which to create the alias
        type: string
      responses:
        200:
          description: OK
      tags:
      - Alias
  /?Action=CreateComputer:
    get:
      summary: Create Computer
      description: Creates a computer account in the specified directory, and joins
        the computer to the directory.
      operationId: createComputer
      x-api-path-slug: actioncreatecomputer-get
      parameters:
      - in: query
        name: ComputerAttributes
        description: An array of Attribute objects that contain any LDAP attributes
          to apply to the            computer account
        type: string
      - in: query
        name: ComputerName
        description: The name of the computer account
        type: string
      - in: query
        name: DirectoryId
        description: The identifier of the directory in which to create the computer
          account
        type: string
      - in: query
        name: OrganizationalUnitDistinguishedName
        description: The fully-qualified distinguished name of the organizational
          unit to place the computer account in
        type: string
      - in: query
        name: Password
        description: A one-time password that is used to join the computer to the
          directory
        type: string
      responses:
        200:
          description: OK
      tags:
      - Computer
  /?Action=CreateConditionalForwarder:
    get:
      summary: Create Conditional Forwarder
      description: Creates a conditional forwarder associated with your AWS directory.
      operationId: createConditionalForwarder
      x-api-path-slug: actioncreateconditionalforwarder-get
      parameters:
      - in: query
        name: DirectoryId
        description: The directory ID of the AWS directory for which you are creating
          the conditional forwarder
        type: string
      - in: query
        name: DnsIpAddrs
        description: The IP addresses of the remote DNS server associated with RemoteDomainName
        type: string
      - in: query
        name: RemoteDomainName
        description: The fully qualified domain name (FQDN) of the remote domain with
          which you will set up a trust relationship
        type: string
      responses:
        200:
          description: OK
      tags:
      - Conditional Forwarder
  /?Action=CreateDirectory:
    get:
      summary: Create Directory
      description: Creates a Simple AD directory.
      operationId: createDirectory
      x-api-path-slug: actioncreatedirectory-get
      parameters:
      - in: query
        name: Description
        description: A textual description for the directory
        type: string
      - in: query
        name: Name
        description: The fully qualified name for the directory, such as corp
        type: string
      - in: query
        name: Password
        description: The password for the directory administrator
        type: string
      - in: query
        name: ShortName
        description: The short name of the directory, such as CORP
        type: string
      - in: query
        name: Size
        description: The size of the directory
        type: string
      - in: query
        name: VpcSettings
        description: A DirectoryVpcSettings object that contains additional information
          for the         operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
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