---
nav-sort: 100
nav-level: 1
---
# Core Schemas
This directory contains schemas for EntityJSON and other core features.

The formal specification of EntityJSON and attribute types is written in JSON Schema Draft 4.

## entity-json
This is the schema for the core of EntityJSON, which is formally identified as http://object.symphonyoss.org/schema/entity-json-vX_Y.json.

This schema defines the format of the EntityJSON object which is submitted when sending messages or which is returned when reading messages through the Symphony Public REST API. This object contains one or more Structured Objects.

[entity-json-v0_1.json](entity-json-v0_1.json)

## structured-object
This schema defines the format of  a single Structured Object.

[structured-object-v0_1.json](structured-object-v0_1.json)

## definitions
This schema defines various objects used in the other schemas.

[definitions-v0_1.json](definitions-v0_1.json)

## core-types
This schema defines the core data types used throughout the schemas.

[core-types-v0_1.json](core-types-v0_1.json)

## org.symphonyoss.fin.types
This schema defines the basic financial types.

[org/symphonyoss/fin/types-v0_1.json](org/symphonyoss/fin/types-v0_1.json)

## org.symphonyoss.country
This schema defines country identifier types.

[org/symphonyoss/country-v0_1.json](org/symphonyoss/country-v0_1.json)