---
title: >-
  Walrus Bayesian State-space Model Output from the Bering Sea and Chukchi Sea,
  2008-2012
created: '2020-11-12T21:03:23.656937'
modified: '2020-11-12T21:03:23.656944'
state: active
type: dataset
tags:
  - Animal Movement
  - Autumn
  - Behavior
  - Bering Sea
  - Biologging
  - Chukchi Sea
  - Kernel Overlap
  - Marine
  - Radio Telemetry
  - Space Use
  - Spring
  - State Space Model
  - Summer
  - Telemetry
  - Utilization Distributions
groups: []
csv_url: 'http://dx.doi.org/10.5066/F77M060G'
json_url: ''
layout: post

---
State-space models offer researchers an objective approach to modeling complex animal location datasets, and state-space model behavior classifications are often assumed to have a link to animal behavior. We evaluated the behavioral classification accuracy of a Bayesian state-space model in Pacific walruses using Argos satellite tags outfitted with sensors to detect animal behavior in real time. Specifically, tags were targeted to attach midway between the shoulders and each tag had a conductivity sensor and pressure transducer sensor integrated with an Argos satellite telemetry tag. At 1 s intervals, the pressure transducer recorded the depth of the tag and the conductivity sensor indicated whether the tag was in salt water. Two simple algorithms that ran onboard the tag summarized behavior information within 1-hr intervals to facilitate behavior data transmission through the Argos system using two indicator variables. One algorithm set the forage indicator variable to 1 if >50% of depth measurements exceeded 10 m during a 1-hr interval and to 0 if otherwise. A second algorithm set the wet indicator variable to 1 if >10% of conductivity measurements indicated the tag was in salt water during that 1-hr interval and to 0 if otherwise. Based on the values of these two indicator variables, we categorized each 1-hr interval into one of three behavior states. A combination of wet = 0 and forage = 0 for a 1-hr interval indicated the animal was primarily hauled-out during that period. Variable indicators of wet = 1 and forage = 0 indicated a walrus was primarily in water and not foraging (swimming) during the associated 1-hr interval. Finally, combinations of wet = 1 and foraging = 1 represented an individual foraging at depth for the corresponding 1-hr interval. To compare these real behaviors to modeled behaviors, we fit a two-state discrete-time continuous-space Bayesian state-space model to data from 306 Pacific walruses tagged in the Chukchi Sea. We matched predicted locations and behaviors from the state-space model (resident, transient behavior) to true animal behavior (foraging, swimming, hauled-out) and evaluated classification accuracy with kappa statistics and root mean square error. These data represent Bayesian state-space model output for 8 hr and 12 hr time steps.
