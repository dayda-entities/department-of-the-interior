---
title: >-
  Argos Satellite Tracking Data for Spectacled Eiders (Somateria fischeri) -
  Processed Data
created: '2020-11-12T20:29:36.834764'
modified: '2020-11-12T20:29:36.834774'
state: active
type: dataset
tags:
  - Alaska
  - Animal Tracking
  - Animalsvertebrates
  - Argos
  - Beaufort Sea
  - Bering Sea
  - Birds
  - Breeding Area
  - Breeding Sites
  - Capture Recapture Studies
  - Chukchi Sea
  - Coastal Ecosystems
  - Colville River Delta
  - Ducksgeeseswans
  - Marine Ecosystems
  - Migratory Birds
  - Migratory Ratesroutes
  - Migratory Species
  - North Slope
  - Ornithology
  - Overwintering
  - Peard Bay
  - Platform Transmitter Terminal
  - Ptt
  - Satellite Transmitter
  - Seasonal Distribution
  - Seasonal Movement
  - Species Life History
  - Spectacled Eider
  - Tagging Devices
  - Telemetry
  - Tracking Equipment
  - Wildlife
  - Wintering Area
  - Yukon Delta
  - Yukon Delta National Wildlife Refuge
groups: []
csv_url: 'https://www.movebank.org/'
json_url: ''
layout: post

---
This metadata document describes the data contained in the "processedData" folder of this data package. This data package contains all data collected by the Argos System from 217 satellite transmitters attached to Spectacled Eiders on their breeding range in arctic and western Alaska and northeastern Russia, 1993-2011. The raw data were processed to accomplish two goals: flag implausible location estimates and decode raw sensor data. Three Comma Separate Value (CSV) tables are included in the "processedData" folder of this data package: 1) the "diag_filteredLocations" table contains one record for every location estimate collected, accompanied by a binary flag that denotes an algorithm's plausibility check. Each record also includes a 'Tracking_Status' variable that denotes whether the location was collected from a live animal, a dead animal, or shed transmitter, 2) the "decodedSensor" table contains decoded sensor data such as a transmitter's temperature, battery voltage, and motion (activity), and 3) the "deploymentAttributes" table contains one record for each transmitter deployment in a CSV formatted table. The deployment attributes file contains information such as when the transmitter was attached to the animal, when tracking of a live animal ended, and a variety of variables describing the animal and transmitter. This table is identical to the "deploymentAttributes" table in the "rawData" folder of this data package.
