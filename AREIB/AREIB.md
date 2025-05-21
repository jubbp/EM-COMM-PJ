# Amatuer Radio Emergency Information Beacon Project <!-- omit from toc -->

## Table of Contents <!-- omit from toc -->

- [Purpose](#purpose)
- [Naming Options](#naming-options)
- [Gathering](#gathering)
  - [A Services Status](#a-services-status)
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

## Purpose

The AREIB is a system of information sharing building situational awareness
among a group of like minded amateru radio operators.



## Naming Options

What should we call this project? Some options for consideration:

- Amateur Radio Information Beacon
- Emergency Communication Beacon
- **TODO:** work on some better alternatives

## Gathering

What sort of information do we need to gather and then store and distribute??

### A Services Status

 a status that may change over time and be updated.

example 1: A Hospital

An Entity:
A person/organisation/location that may have some sort of status indicator

```json
"entity": {
  "name": String,
  "hierachy" {
    ....
  }
}

"location": {
    "type": string,        // (fixed,roaming)
    "lat": string,         // (-33.123456)
    "lon": String,         // (115.123456)
    "locator" : String,    // (OF76to)
    "streetAddr" : String, // (Cnr William & Hay St)
    "source": String       // "GPS","Manual"
  }


"status": {
    "code": Integer,          // (0-5)
    "time": dateTime String,  // ()
    "message" : String,       // "Situation Normal"
    "ttl" : integer           // Seconds for information to be valid
}

"resource": {
  "name": String

}

```

**TODO:** How will we gather the information?


## Storing

**TODO:** How will we store the information?

- Messages should have a priority
- Messages should have expiry

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

- Basic Information
- Service Status
- Assistance Request

## Desceminating

How will we get thi information out of the system?

### BEACONS

Setup and beacon on a predefined frequency that will trasmit voice information

- Beacon should announce itself
- Beacon will read "messages" stored in the system using voice to text
- Beacon should annouce how to participate

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
