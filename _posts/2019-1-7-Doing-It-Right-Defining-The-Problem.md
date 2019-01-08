---
layout: post
title: "Doing It Right: Defining The Problem"
---

## Overview

First, we define the problem at a high level; then we define the problem in enough detail to build a solution. These problem constraints were dictated by the Interface Control Document (ICD) that was written before I started on the project. Note that some details are being changed for the sake of highlighting the core problems. 

## High-Level Description

Three hospital databases serve similar kinds of documents for the same person, but each belongs to a different organization. These three organizations want the databases to be searchable via a REST web service in a convenient manner, so that a new health care service can search through a patients' data stored at hospitals. To accomplish this, they propose the following:

* an HTTP web service (not necessarily REST, though they call it such) will be an interface between the new health care service and the three databases, as below;
  
  ![]() TODO: add architecture layout. 
  
* the HTTP web service will be asynchronous and ticket-based ("start the operation and give me a ticket number; I'll ping you with this ticket number every two seconds until you're done searching");

* the web service will consist of two parts: a metadata search ("give me document ids and document names for person X in date range Y-Z") and a document retrieval ("give me the document for document id A").

## Detailed Description

TODO: add a detailed description. 
