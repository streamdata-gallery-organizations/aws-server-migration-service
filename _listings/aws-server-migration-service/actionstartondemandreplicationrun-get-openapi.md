---
swagger: "2.0"
x-collection-name: AWS Server Migration Service
x-complete: 0
info:
  title: AWS Server Migration Service API Start On Demand Replication Run
  version: 1.0.0
  description: The start-on-demand-replication-run API is used to start a ReplicationRun
    on demand (in addition to those that are scheduled based on your frequency).
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateReplicationJob:
    get:
      summary: Create Replication Job
      description: The create-replication-job API is used to create a ReplicationJob
        to replicate a server on AWS.
      operationId: createReplicationJob
      x-api-path-slug: actioncreatereplicationjob-get
      parameters:
      - in: query
        name: description
        description: 'Type: String'
        type: string
      - in: query
        name: frequency
        description: 'Type: Integer'
        type: string
      - in: query
        name: licenseType
        description: 'Type: String'
        type: string
      - in: query
        name: roleName
        description: 'Type: String'
        type: string
      - in: query
        name: seedReplicationTime
        description: 'Type: Timestamp'
        type: string
      - in: query
        name: serverId
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Jobs
  /?Action=DeleteReplicationJob:
    get:
      summary: Delete Replication Job
      description: The delete-replication-job API is used to delete a ReplicationJob,
        resulting in no further ReplicationRuns.
      operationId: deleteReplicationJob
      x-api-path-slug: actiondeletereplicationjob-get
      parameters:
      - in: query
        name: replicationJobId
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Jobs
  /?Action=DeleteServerCatalog:
    get:
      summary: Delete Server Catalog
      description: The delete-server-catalog API clears all servers from your server
        catalog.
      operationId: deleteServerCatalog
      x-api-path-slug: actiondeleteservercatalog-get
      responses:
        200:
          description: OK
      tags:
      - Server Catalog
  /?Action=DisassociateConnector:
    get:
      summary: Disassociate Connector
      description: The disassociate-connector API will disassociate a connector from
        the Server Migration Service, rendering it unavailable to support replication
        jobs.
      operationId: disassociateConnector
      x-api-path-slug: actiondisassociateconnector-get
      parameters:
      - in: query
        name: connectorId
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connectors
  /?Action=GetConnectors:
    get:
      summary: Get Connectors
      description: The get-connectors API returns a list of connectors that are registered
        with the Server Migration Service.
      operationId: getConnectors
      x-api-path-slug: actiongetconnectors-get
      parameters:
      - in: query
        name: maxResults
        description: 'Type: Integer'
        type: string
      - in: query
        name: nextToken
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Connectors
  /?Action=GetReplicationJobs:
    get:
      summary: Get Replication Jobs
      description: The get-replication-jobs API will return all of your ReplicationJobs
        and their details.
      operationId: getReplicationJobs
      x-api-path-slug: actiongetreplicationjobs-get
      parameters:
      - in: query
        name: maxResults
        description: 'Type: Integer'
        type: string
      - in: query
        name: nextToken
        description: 'Type: String'
        type: string
      - in: query
        name: replicationJobId
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Jobs
  /?Action=GetReplicationRuns:
    get:
      summary: Get Replication Runs
      description: The get-replication-runs API will return all ReplicationRuns for
        a given ReplicationJob.
      operationId: getReplicationRuns
      x-api-path-slug: actiongetreplicationruns-get
      parameters:
      - in: query
        name: maxResults
        description: 'Type: Integer'
        type: string
      - in: query
        name: nextToken
        description: 'Type: String'
        type: string
      - in: query
        name: replicationJobId
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Runs
  /?Action=GetServers:
    get:
      summary: Get Servers
      description: The get-servers API returns a list of all servers in your server
        catalog.
      operationId: getServers
      x-api-path-slug: actiongetservers-get
      parameters:
      - in: query
        name: maxResults
        description: 'Type: Integer'
        type: string
      - in: query
        name: nextToken
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Servers
  /?Action=ImportServerCatalog:
    get:
      summary: Import Server Catalog
      description: The import-server-catalog API is used to gather the complete list
        of on-premises servers on your premises.
      operationId: importServerCatalog
      x-api-path-slug: actionimportservercatalog-get
      responses:
        200:
          description: OK
      tags:
      - Server Catalog
  /?Action=StartOnDemandReplicationRun:
    get:
      summary: Start On Demand Replication Run
      description: The start-on-demand-replication-run API is used to start a ReplicationRun
        on demand (in addition to those that are scheduled based on your frequency).
      operationId: startOnDemandReplicationRun
      x-api-path-slug: actionstartondemandreplicationrun-get
      parameters:
      - in: query
        name: description
        description: 'Type: String'
        type: string
      - in: query
        name: replicationJobId
        description: 'Type: String'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Replication Runs
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