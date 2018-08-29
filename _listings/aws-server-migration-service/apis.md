---
name: AWS Server Migration Service
x-slug: aws-server-migration-service
description: AWS Server Migration Service (SMS) is an agentless service which makes
  it easier and faster for you to migrate thousands of on-premises workloads to AWS.
  AWS SMS allows you to automate, schedule, and track incremental replications of
  live server volumes, making it easier for you to coordinate large-scale server migrations.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Server Migration Service
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Server Migration Service API - Create Replication Job
  x-api-slug: actioncreatereplicationjob-get
  description: The create-replication-job API is used to create a ReplicationJob to
    replicate a server on AWS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actioncreatereplicationjob-get-openapi.md
- name: AWS Server Migration Service API - Delete Replication Job
  x-api-slug: actiondeletereplicationjob-get
  description: The delete-replication-job API is used to delete a ReplicationJob,
    resulting in no further ReplicationRuns.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiondeletereplicationjob-get-openapi.md
- name: AWS Server Migration Service API - Delete Server Catalog
  x-api-slug: actiondeleteservercatalog-get
  description: The delete-server-catalog API clears all servers from your server catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiondeleteservercatalog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiondeleteservercatalog-get-openapi.md
- name: AWS Server Migration Service API - Disassociate Connector
  x-api-slug: actiondisassociateconnector-get
  description: The disassociate-connector API will disassociate a connector from the
    Server Migration Service, rendering it unavailable to support replication jobs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiondisassociateconnector-get-openapi.md
- name: AWS Server Migration Service API - Get Connectors
  x-api-slug: actiongetconnectors-get
  description: The get-connectors API returns a list of connectors that are registered
    with the Server Migration Service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiongetconnectors-get-openapi.md
- name: AWS Server Migration Service API - Get Replication Jobs
  x-api-slug: actiongetreplicationjobs-get
  description: The get-replication-jobs API will return all of your ReplicationJobs
    and their details.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiongetreplicationjobs-get-openapi.md
- name: AWS Server Migration Service API - Get Replication Runs
  x-api-slug: actiongetreplicationruns-get
  description: The get-replication-runs API will return all ReplicationRuns for a
    given ReplicationJob.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiongetreplicationruns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiongetreplicationruns-get-openapi.md
- name: AWS Server Migration Service API - Get Servers
  x-api-slug: actiongetservers-get
  description: The get-servers API returns a list of all servers in your server catalog.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actiongetservers-get-openapi.md
- name: AWS Server Migration Service API - Import Server Catalog
  x-api-slug: actionimportservercatalog-get
  description: The import-server-catalog API is used to gather the complete list of
    on-premises servers on your premises.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actionimportservercatalog-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actionimportservercatalog-get-openapi.md
- name: AWS Server Migration Service API - Start On Demand Replication Run
  x-api-slug: actionstartondemandreplicationrun-get
  description: The start-on-demand-replication-run API is used to start a ReplicationRun
    on demand (in addition to those that are scheduled based on your frequency).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actionstartondemandreplicationrun-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actionstartondemandreplicationrun-get-openapi.md
- name: AWS Server Migration Service API - Update Replication Job
  x-api-slug: actionupdatereplicationjob-get
  description: The update-replication-job API is used to change the settings of your
    existing ReplicationJob created using CreateReplicationJob.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2_AMI.png
  humanURL: https://aws.amazon.com/server-migration-service/
  baseURL: :///
  tags: Amazon Web Services, Stack Network, API Service Provider, API Service Provider,
    API Provider, Databases, Migrations, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-server-migration-service/master/_listings/aws-server-migration-service/actionupdatereplicationjob-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.security.token.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.server.migration.service.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/server-migration-service/latest/userguide/cli_workflow.html
- type: x-documentation
  url: http://docs.aws.amazon.com/ServerMigration/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/server-migration-service/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/server-migration-service/getting-started/
- type: x-partners
  url: https://aws.amazon.com/server-migration-service/partners/
- type: x-pricing
  url: https://aws.amazon.com/server-migration-service/pricing/
- type: x-website
  url: https://aws.amazon.com/server-migration-service/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---