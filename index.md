# CY OOTS Integration Guide

## Introduction
The **Single Digital Gateway Regulation (SDGR)** aims to digitize and simplify access to cross-border procedures across the European Union, thus helping citizens and businesses make the best of the Single Market. To implement this, the OOTS was conceptualised, to allow service providers to retrieve authenticated evidence about a user directly from the originating Member State. Consisting of multiple components (labelled as "building blocks"), this implementation of the OOTS seeks to largely abstract these building blocks behind a single Integration Layer, accessible via a REST API.  

The system concerns an Evidence Exchange between two separate Member States: the Member State of the citizen wherein the Evidence is stored, and the Member State of the procedure requesting the use of the same Evidence. In the case of the former, the entity storing the Evidence is known as an Evidence Provider (EP), whereas in the latter, the procedure belongs to an Evidence Requester (ER).

**OOTS is the technical system for the cross-border automated exchange of evidence.**  The CY SDG OOTS Integration components are intended to serve as an intermediary - for Evidence Requesters (Procedure Portals) and Evidence Providers - with core OOTS services. This design allows integrators to connect with OOTS much more seamlessly, by abstracting the Evidence Exchange flow into API calls.


## Definitions
| Term  | Definition  |Description|
|--- |---|---|
|SDG |Single Digital Gateway|The regulation in which article 14 sets the requirement to establish a technical system for the automated exchange of evidence between competent authorities in different Member States|
|OOTS|Once Only Technical System|The technical system for the cross-border automated exchange of evidence|
|CA  |Competent authority|Competent authority means any Member State authority or body established at national, regional or local level with specific responsibilities relating to the information, procedures, assistance and services covered by the SDGR|
|EP  |Evidence Provider|The competent authority which is providing the evidence|
|ER  |Evidence Requester|A webpage or a mobile application where a user can access and complete an online procedure|
|EB  |Evidence Broker|The Evidence Broker is an authoritative system that maps specific data sets as evidence types that prove specific requirements|
|DSD |Data Services Directory|The Data Service Directory is a common service that acts as a catalogue of evidence types that can be provided upon request|
|SR  |Semantic Repository|The Semantic Repository is a common service that acts as a data portal for the technical system|

## User Journey

## OOTS High-Level Architecture

## Disclaimers

### Audit Logs



