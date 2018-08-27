---
name: AWS Database Migration Service
x-slug: aws-database-migration-service
description: AWS Database Migration Service helps you migrate databases to AWS easily
  and securely. The source database remains fully operational during the migration,
  minimizing downtime to applications that rely on the database. The AWS Database
  Migration Service can migrate your data to and from most widely used commercial
  and open-source databases. The service supports homogenous migrations such as Oracle
  to Oracle, as well as heterogeneous migrations between different database platforms,
  such as Oracle to Amazon Aurora or Microsoft SQL Server to MySQL. It also allows
  you to stream data to Amazon Redshift from any of the supported sources including
  Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, SAP ASE and SQL Server, enabling
  consolidation and easy analysis of data in the petabyte-scale data warehouse. AWS
  Database Migration Service can also be used for continuous data replication with
  high-availability.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Action
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Database Migration Service API - Add Tags To Resource
  x-api-slug: actionaddtagstoresource-get
  description: Adds metadata tags to a DMS resource, including replication instance,
    endpoint, security group, and migration task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionaddtagstoresource-get-openapi.md
- name: AWS Database Migration Service API - Create Endpoint
  x-api-slug: actioncreateendpoint-get
  description: Creates an endpoint using the provided settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actioncreateendpoint-get-openapi.md
- name: AWS Database Migration Service API - Create Replication Instance
  x-api-slug: actioncreatereplicationinstance-get
  description: Creates the replication instance using the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actioncreatereplicationinstance-get-openapi.md
- name: AWS Database Migration Service API - Create Replication Subnet Group
  x-api-slug: actioncreatereplicationsubnetgroup-get
  description: Creates a replication subnet group given a list of the subnet IDs in
    a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actioncreatereplicationsubnetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actioncreatereplicationsubnetgroup-get-openapi.md
- name: AWS Database Migration Service API - Create Replication Task
  x-api-slug: actioncreatereplicationtask-get
  description: Creates a replication task using the specified parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actioncreatereplicationtask-get-openapi.md
- name: AWS Database Migration Service API - Delete Certificate
  x-api-slug: actiondeletecertificate-get
  description: Deletes the specified certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondeletecertificate-get-openapi.md
- name: AWS Database Migration Service API - Delete Endpoint
  x-api-slug: actiondeleteendpoint-get
  description: Deletes the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondeleteendpoint-get-openapi.md
- name: AWS Database Migration Service API - Delete Replication Instance
  x-api-slug: actiondeletereplicationinstance-get
  description: Deletes the specified replication instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondeletereplicationinstance-get-openapi.md
- name: AWS Database Migration Service API - Delete Replication Subnet Group
  x-api-slug: actiondeletereplicationsubnetgroup-get
  description: Deletes a subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondeletereplicationsubnetgroup-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondeletereplicationsubnetgroup-get-openapi.md
- name: AWS Database Migration Service API - Delete Replication Task
  x-api-slug: actiondeletereplicationtask-get
  description: Deletes the specified replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondeletereplicationtask-get-openapi.md
- name: AWS Database Migration Service API - Describe Account Attributes
  x-api-slug: actiondescribeaccountattributes-get
  description: Lists all of the AWS DMS attributes for a customer account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeaccountattributes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeaccountattributes-get-openapi.md
- name: AWS Database Migration Service API - Describe Certificates
  x-api-slug: actiondescribecertificates-get
  description: Provides a description of the certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribecertificates-get-openapi.md
- name: AWS Database Migration Service API - Describe Connections
  x-api-slug: actiondescribeconnections-get
  description: Describes the status of the connections that have been made between
    the replication instance and an endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeconnections-get-openapi.md
- name: AWS Database Migration Service API - Describe Endpoints
  x-api-slug: actiondescribeendpoints-get
  description: Returns information about the endpoints for your account in the current
    region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeendpoints-get-openapi.md
- name: AWS Database Migration Service API - Describe Endpoint Types
  x-api-slug: actiondescribeendpointtypes-get
  description: Returns information about the type of endpoints available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeendpointtypes-get-openapi.md
- name: AWS Database Migration Service API - Describe Orderable Replication Instances
  x-api-slug: actiondescribeorderablereplicationinstances-get
  description: Returns information about the replication instance types that can be
    created in the specified region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeorderablereplicationinstances-get-openapi.md
- name: AWS Database Migration Service API - Describe Refresh Schemas Status
  x-api-slug: actiondescriberefreshschemasstatus-get
  description: Returns the status of the RefreshSchemas operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescriberefreshschemasstatus-get-openapi.md
- name: AWS Database Migration Service API - Describe Replication Instances
  x-api-slug: actiondescribereplicationinstances-get
  description: Returns information about replication instances for your account in
    the current region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribereplicationinstances-get-openapi.md
- name: AWS Database Migration Service API - Describe Replication Subnet Groups
  x-api-slug: actiondescribereplicationsubnetgroups-get
  description: Returns information about the replication subnet groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribereplicationsubnetgroups-get-openapi.md
- name: AWS Database Migration Service API - Describe Replication Tasks
  x-api-slug: actiondescribereplicationtasks-get
  description: Returns information about replication tasks for your account in the
    current region.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribereplicationtasks-get-openapi.md
- name: AWS Database Migration Service API - Describe Schemas
  x-api-slug: actiondescribeschemas-get
  description: Returns information about the schema for the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribeschemas-get-openapi.md
- name: AWS Database Migration Service API - Describe Table Statistics
  x-api-slug: actiondescribetablestatistics-get
  description: Returns table statistics on the database migration task, including
    table name, rows inserted, rows updated, and rows deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribetablestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiondescribetablestatistics-get-openapi.md
- name: AWS Database Migration Service API - Import Certificate
  x-api-slug: actionimportcertificate-get
  description: Uploads the specified certificate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionimportcertificate-get-openapi.md
- name: AWS Database Migration Service API - List Tags For Resource
  x-api-slug: actionlisttagsforresource-get
  description: Lists all tags for an AWS DMS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionlisttagsforresource-get-openapi.md
- name: AWS Database Migration Service API - Modify Endpoint
  x-api-slug: actionmodifyendpoint-get
  description: Modifies the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionmodifyendpoint-get-openapi.md
- name: AWS Database Migration Service API - Modify Replication Instance
  x-api-slug: actionmodifyreplicationinstance-get
  description: Modifies the replication instance to apply new settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionmodifyreplicationinstance-get-openapi.md
- name: AWS Database Migration Service API - Modify Replication Subnet Group
  x-api-slug: actionmodifyreplicationsubnetgroup-get
  description: Modifies the settings for the specified replication subnet group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionmodifyreplicationsubnetgroup-get-openapi.md
- name: AWS Database Migration Service API - Modify Replication Task
  x-api-slug: actionmodifyreplicationtask-get
  description: Modifies the specified replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionmodifyreplicationtask-get-openapi.md
- name: AWS Database Migration Service API - Refresh Schemas
  x-api-slug: actionrefreshschemas-get
  description: Populates the schema for the specified endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionrefreshschemas-get-openapi.md
- name: AWS Database Migration Service API - Remove Tags From Resource
  x-api-slug: actionremovetagsfromresource-get
  description: Removes metadata tags from a DMS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionremovetagsfromresource-get-openapi.md
- name: AWS Database Migration Service API - Start Replication Task
  x-api-slug: actionstartreplicationtask-get
  description: Starts the replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionstartreplicationtask-get-openapi.md
- name: AWS Database Migration Service API - Stop Replication Task
  x-api-slug: actionstopreplicationtask-get
  description: Stops the replication task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actionstopreplicationtask-get-openapi.md
- name: AWS Database Migration Service API - Test Connection
  x-api-slug: actiontestconnection-get
  description: Tests the connection between the replication instance and the endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Database_AWSDatabaseMigrationService.png
  humanURL: https://aws.amazon.com/dms/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/action/master/_listings/aws-database-migration-service/actiontestconnection-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.data.pipeline.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.database.migration.service.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/dms/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/dms/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/dms/getting-started/
- type: x-partners
  url: https://aws.amazon.com/dms/partners/
- type: x-pricing
  url: https://aws.amazon.com/dms/pricing/
- type: x-schema-conversion
  url: https://aws.amazon.com/dms/#sct
- type: x-testimonials
  url: https://aws.amazon.com/dms/testimonials/
- type: x-website
  url: https://aws.amazon.com/dms/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---