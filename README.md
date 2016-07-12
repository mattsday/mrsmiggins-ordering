# Mrs Miggins Ordering Service
An example microservices app built on Cisco Mantl to order and track pies

# Containers
These are all in the containers folder:

## api-gateway
This is a microservices front-end that accepts requests from various services (web, spark, ...)

It will broker to the various services

## inventory-system
Holds information on inventory and product catalogue

## inventory-system-db
Database container

## media-system
Provides images and multi-media services

## media-system-db
Database container

## customer-system
Manages customer accounts and information

## order-system
Holds state on orders and transactions

## web-frontend
Main method to access the system - via the web

## spark-frontend
Direct access to the system via spark (requires public access)

## spark-proxy-frontend
Indirect access (i.e. via proxy/DMZ) to Spark

## spark-proxy-webhook
Webhook for spark

