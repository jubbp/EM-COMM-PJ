# Amatuer Radio Emergency Information Beacon Project <!-- omit from toc -->

## Table of Contents <!-- omit from toc -->

- [Naming Options](#naming-options)
- [Gathering](#gathering)
- [Storing](#storing)
  - [Basic Message Storage](#basic-message-storage)
  - [Service Status Message Storage](#service-status-message-storage)
  - [Message Types](#message-types)
- [Desceminating](#desceminating)
  - [BEACONS](#beacons)
  - [APRS](#aprs)
  - [PACKET BBS?](#packet-bbs)
  - [AREDN](#aredn)
  - [WEB](#web)
  - [HF Digtial](#hf-digtial)


Lets design an information, gathering, storing and deceminating system.

## Naming Options

What should we call this project? Some options for consideration:

* Amateur Radio Information Beacon
* Emergency Communication Beacon
* **TODO:** work on some better alternatives

## Gathering

**TODO:** How will we gather the information?

## Storing

**TODO:** How will we store the information?

* Messages should have a priority
* Messages should have expiry

Lets define a data model...

### Basic Message Storage

```json
{
    "id"      : Number,      # Unique Message ID
    "type"    : String,      #
    "created" : datetime,
    "callsign": String,
    "priority": Number,
    "message" : String,
    "ttl"     : Number
}
```

### Service Status Message Storage

```json
{
    "id"      : Number,
    "type"    : String,
    "created" : datetime,
    "callsign": String,
    "priority": Number,
    "message" : String,
    "ttl"     : Number
}
```

### Message Types

* Basic Information
* Service Status
* Assistance Request
* 

## Desceminating

### BEACONS

Setup and beacon on a predefined frequency that will trasmit voice information

* Beacon should announce itself
* Beacon will read "messages" stored in the system using voice to text
* Beacon should annouce how to participate

### APRS

Should we beacon messages or should be be on request?
Possibly, beacon that system is active, message retrieval by request??

### PACKET BBS?

Should we make the messages available by packet radio in a BBS style interface?

### AREDN

Should we make a web interface available on the AREDN network??

### WEB

Should we make a web/API interface available on the internet??

### HF Digtial

JS8CALL etc.....
