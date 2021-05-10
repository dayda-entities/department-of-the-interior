---
title: >-
  Argos Satellite Tracking Data for Northern Pintails (Anas acuta) - Processed
  Data
created: '2020-11-12T19:17:50.255555'
modified: '2020-11-12T19:17:50.255562'
state: active
type: dataset
tags:
  - Animal Tracking
  - Animalsvertebrates
  - Argos
  - Biological Classification
  - Birds
  - Breeding Area
  - Breeding Sites
  - Distribution
  - Ducksgeeseswans
  - East Asia Flyway
  - Ecological Dynamics
  - Field Methods
  - Field Sampling
  - Hokkaido
  - Honshu
  - Iwate
  - Izunuma
  - Japan
  - Migration
  - Migration Organisms
  - Migration Pathway
  - Migratory Birds
  - Migratory Strategies
  - North Pacific Ocean
  - Ornithology
  - Overwintering
  - Platform Transmitter Terminal
  - Ptt
  - Russia
  - Satellite Transmitter
  - Seasonal Distribution
  - Seasonal Movement
  - Siberia
  - Species Life History
  - Species Migration
  - Telemetry
  - Tracking Equipment
  - Wildlife Biology
  - Wintering Area
groups: []
csv_url: 'https://www.movebank.org/'
json_url: ''
layout: post

---
This metadata document describes the data contained in the "processedData" folder of this data package. This data package contains all data collected by the Argos System from 129 satellite transmitters attached to Northern Pintail ducks on their winter range in Japan, 2007-2009. The raw data were processed to accomplish two goals: flag implausible location estimates and decode raw sensor data. Three Comma Separate Value (CSV) tables are included in the "processedData" folder of this data package: 1) the "diag_filteredLocations" table contains one record for every location estimate collected, accompanied by a binary flag that denotes an algorithm's plausibility check. Each record also includes a 'Tracking_Status' variable that denotes whether the location was collected from a live animal, a dead animal, or shed transmitter, 2) the "decodedSensor" table contains decoded sensor data such as a transmitter's temperature, battery voltage, and motion (activity), and 3) the "deploymentAttributes" table contains one record for each transmitter deployment in a CSV formatted table. The deployment attributes file contains information such as when the transmitter was attached to the animal, when tracking of a live animal ended, and a variety of variables describing the animal and transmitter. This table is identical to the "deploymentAttributes" table in the "rawData" folder of this data package.
