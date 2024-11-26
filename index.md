# CY OOTS Integration Guide

## Introduction
The Single Digital Gateway Regulation aims to digitize and simplify access to cross-border procedures across the European Union, thus helping citizens and businesses make the best of the Single Market. To implement this, the OOTS was conceptualised, to allow service providers to retrieve authenticated evidence about a user directly from the originating Member State. Consisting of multiple components (labelled as "building blocks"), this implementation of the OOTS seeks to largely abstract these building blocks behind a single Integration Layer, accessible via a REST API.  

The CY SDG OOTS Integration API is intended to serve as an intermediary - for Evidence Requesters (Procedure Portals) and Evidence Providers - with core OOTS services. This design allows integrators to connect with OOTS much more seamlessly, by abstracting the Evidence Exchange flow into API calls.
