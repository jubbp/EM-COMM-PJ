# Emcomm Notes by Phil VK6DEV

<img src="./Images/IMG_1691.PNG" width="100" alt="EmComm Logo">

## 🦺 Table of Contents

* [Introduction](./README#introduction)
* [Security Considerations](./README#security-considerations)
* [Tools](./README#tools)
* [Reference Resources](README#reference-resources)
* [Emergency Services Radio](README#emergency-services-radio)
* [Amateur Radio Emergency Information Beacon Project](README#amatuer-radio-emergency-beacon-project)

## 🦺 Introduction

This document is my work to investigate and document an emcomms methodology.
This EmComm plan is designed for my own use and as such will largely focus on
Western Australia 🇦🇺, but the concepts will be transferable to most locations. 

This is a living document, it will change and grow over time so make sure you 
come back regularly.

Collaboration is encouraged. These documents hosted on GitHub and editable by all.

Please feel free to contact me <vk6dev@gmail.com>

### 🦺 What is EmComm?

EmComm is short for Emergency Communications. It is a procedure/method
 of maintaining reliable and effective communications during an emergency.
An EmComm system should help in the collection, collation and distribution
of information during an emergency situation where mainstream communications
maybe disrupted.

EmComm should not be about any one particular technology or mode of
communication, but should be about the communication itself.

### 🦺 Why do we need EmComm?

In the event of a disruption to normal life, communication is a vital resource
for all. This is where EmComm and Amateur Radio Operators can step up to assist
the community.

### 🦺 Who may need our assistance

There are many who may need our assistance. They are probably not those that
you might think of first.
In Western Australia, the emergency services are served by an extensive
communication network whihc is multi-redundant and resilient. See the section
of [Emergecy Services Radio resources](./README#emergency-services-radio).

* Community Organisations
* Local Government
* Other Amateurs
* Our Family
* Our Friends

How will we interact with the wider community? How will we assist those
organisations that need communications during an emergency.

## 🦺 Security Considerations

The security of our communications could be important to us. As the communications
methods described in this plan will be predominantly based on Amateur Radio,
it is important to remember that no encryption is allowed in on the Amateur Radio
Bands.

There are ways you can obfuscate your communications to make them less obvious.

* Use "non-standard" frequencies
* Digital rather than analogue
* Code words and predefined phrases
* Use a commercial service where encryption is allowed

## 🦺 Information is King

During an emergency event, access to information is of utmost importance. Without
timely and accurate information you can not make decisions which may affect you,
your family and friends.

To gather information you can:

* Listen to official radio sources
* listen to broadcast radio
* read official govt information
* read/listen/watch media reports
* listen to your local amateur radio news

A central location for verified information is important. From this central location
others should be able retieve the information.

## 🦺 Training

Like everything we do in life, **practice makes perfect**
Having a methodology for emergency communications is no good is you don’t know
it works.
If nobody knows how to use it, how will they know how to do it when it’s really needed.

* drills
* nets

## 🦺 Tools

* Analogue Voice
* Digital Voice
* [APRS](./APRS.MD)
* APRS Messaging
* [Winlink email](./Winlink.md)
* JS8Call
* VaraAC
* AREDN
* email
* [aprsd](./aprsd.md)

**TODO:**  "How to" page for basic operation of each tool.

## 🦺 Resources

A list of resources usefull when developing an EmComm strategy.

### 🦺 Software Projects

* Digipi
* EmCommTools

## 🦺 Reference Resources

Below is some reference material collected from various sources. 

### 🦺 Emergency Services Radio

The Emergency Services in Western Australia operate several command and control
radio networks. The WA Police operate a secure encrypted voice and data network.

I have little information about St John Ambulance.  
DEFS runs the WAERN mostly on FM.  
DPAW uses VHF FM.

The following frequency lists were found on the internet. The information was
dated 2016 which make it significantly old. I have included the original source
PDF but have also included a document which indicates if I have confirmed the
frequency.

[WAERN Frequency List (Markdown)](./ESR.md)  
[WAERN Frequency List (PDF)](./Resources/WARSUG-WAERN-freqs.pdf)  
[WAERN Channel (Chirp Import CSV)](./Resources/WAERN-FREQ-IMPORT-CHIRP.csv)

### 🦺 Citizens Band (CB) Radio Frequencies

**UHF CB** Frequencies
| Channel | Frequency | Notes |
| --- | --- | --- |
| 1 | 476.425000 | |
| 2 | 476.450000 | |
| 3 | 476.475000 | |
| 4 | 476.500000 | |
| 5 | 476.525000 | Emergency |
| 6 | 476.550000 | |
| 7 | 476.575000 | |
| 8 | 476.600000 | |
| 9 | | |
| 10 | 476.650000 | |
| 11 | 476.675000 | |
| 12 | 476.700000 | |
| 13 | 476.725000 | |
| 14 | 476.750000 | |
| 15 | 476.775000 | |
| 16 | 476.800000 | |
| 17 | 476.825000 | |
| 18 | 476.850000 | Caravans and convoys |
| 19 | 476.875000 | |
| 20 | 476.900000 | |
| 21 | 476.925000 | |
| 22 | | |
| 23 | | |
| 24 | 477.000000 | |
| 25 | 477.025000 | |
| 26 | 477.050000 | |
| 27 | 477.075000 | |
| 28 | 477.100000 | |
| 29 | 477.125000 | |
| 30 | 477.150000 | |
| 31 | | |
| 32 | | |
| 33 | | |
| 34 | | |
| 35 | | |
| 36 | | |
| 37 | | |
| 38 | | |
| 39 | 477.375000 | |
| 40 | 477.400000 | |
| 41 | | |
| 42 | | |
| 43 | | |
| 44 | | |
| 45 | | |
| 46 | | |
| 47 | | |
| 48 | | |
| 49 | 476.637500 | |
| 50 | 476.662500 | |
| 51 | 476.687500 | |
| 52 | 476.712500 | |
| 53 | 476.737500 | |
| 54 | 476.762500 | |
| 55 | 476.787500 | |
| 56 | 476.812500 | |
| 57 | 476.837500 | |
| 58 | 476.862500 | |
| 59 | 476.887500 | |
| 60 | | |
| 61 | | |
| 62 | | |
| 63 | | |
| 64 | | |
| 65 | | |
| 66 | | |
| 67 | | |
| 68 | | |
| 69 | | |
| 70 | | |
| 71 | | |
| 72 | | |
| 73 | | |
| 74 | | |
| 75 | | |
| 76 | | |
| 77 | | |
| 78 | | |
| 79 | | |

**HF CB** Fequencies

| Channel | Frequency | Notes |
| --- | --- | --- |
| 1 | 26.965 Mhz | |
| 2 | 26.975 Mhz | |
| 3 | 26.985 Mhz | |
| 4 | 27.005 Mhz | |
| 5 | 27.015 Mhz | |
| 6 | 27.025 Mhz | |
| 7 | 27.035 Mhz | |
| 8 | 27.055 Mhz | |
| 9 | 27.065 Mhz | Emergency |
| 10 | 27.075 Mhz | |
| 11 | 27.085 Mhz | Call |
| 12 | 27.105 Mhz | |
| 13 | 27.115 Mhz | |
| 14 | 27.125 Mhz | |
| 15 | 27.135 Mhz | |
| 16 | 27.155 Mhz | Call |
| 17 | 27.165 Mhz | |
| 18 | 27.175 Mhz | |
| 19 | 27.185 Mhz | |
| 20 | 27.205 Mhz | |
| 21 | 27.215 Mhz | |
| 22 | 27.225 Mhz | |
| 23 | 27.245 Mhz | |
| 24 | 27.235 Mhz | |
| 25 | 27.255 Mhz | |
| 26 | 27.265 Mhz | |
| 27 | 27.275 Mhz | |
| 28 | 27.285 Mhz | |
| 29 | 27.295 Mhz | |
| 30 | 27.305 Mhz | |
| 31 | 27.315 Mhz | |
| 32 | 27.325 Mhz | |
| 33 | 27.335 Mhz | |
| 34 | 27.345 Mhz | |
| 35 | 27.355 Mhz | |
| 36 | 27.365 Mhz | |
| 37 | 27.375 Mhz | |
| 38 | 27.385 Mhz | |
| 39 | 27.395 Mhz | |
| 40 | 27.405 Mhz | |

## 🦺 Amatuer Radio Emergency Beacon Project

Lets design an information, gathering, storing and deceminating system.

Check out the [design and specifications](./AREIB/AREIB.md)
