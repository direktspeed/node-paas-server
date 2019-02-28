# node-paas-server
A Serverless PaaS Server written in NodeJS - Mainllayer of the DIREKTSPEED Serverless Framework

No Matter if you want to run Serverless Functions or Offer a Uniq Interface for your PaaS Applications PaaS Server gets you up and Running in No Time.

It even circumvents all the downsides that are mentoined here https://serverless.com/blog/when-why-not-use-serverless/
as we give you this visibility.

It is easy Extend and Adjust Able to Serve as Entry Point or event emitter to all your PaaS Applications 

## Install
node-parse-server has 3 Components

- node-paas-server cli (paas command) acccess to templates and configuration for node-paas-socket
- node-paas-socket (agent&daemon)
  - Features
    - Can access Hosts via SSH
    - Can be configured via filesystem, ENV, db
    - Supports diffrent Messaging Frameworks
    - Acts as IPC and Messaging Exchange Layer
    - Supports Encrypted Communication.
- node-paas-ui (Manage Users, and node-paas-socket instances)

## Addons
- node-paas-serverless (Runs Serverless Functions
- node-paas-db (Abstraction layer over database api's)
  - Supports event based API via node-paas-socket
  - node-paas-couchbase (Couchbase Client for node-paas-db)
  - node-paas-node-db (Node Based Custom Database)

## Useage 
Install and Run It with Prefered Auth Algo
- SSH
- Messaging Systems
- HTTP

## Extend it

- How to write Extensions for DIREKTSPEED PaaS
- 


## Use Cases
- Run it on a Docker Host or Docker API Endpoint to Controll Access to the docker api
- Run it on a Host that has access to a Kubernetes or any other Cloud Provider API
