% Indicators and assessment
% Torsten Berg, MariLim GmbH
% 2017-09-28

---
% This is a Pandoc markdown file, used to produce a nice PDF-file
% This file can be viewed directly on github, but some of Pandoc's
% features will not be visible there, such as metadata and references
---

# Introduction

In Europe, over 200 pieces of legislation with direct direct relationship to marine waters exist [@boyes-2014]. Most of them only deal with one sector of marine sustainable use and protection (such as nitrate, litter, oil, marine habitats). Many were driven by societal concerns and urgent needs (increasing visible pollution), often targeting specific environmental problems. Over the years, harmonizing these policies has lead to a complex management task, sometimes with conflicting demands.

Gradually, these sectoral directives are superseded or subsumed into holistic frameworks such as the [Marine Strategy Framework Directive](http://ec.europa.eu/environment/marine/eu-coast-and-marine-policy/marine-strategy-framework-directive/index_en.htm) (MSFD). They call for integrative assessment and an ecosystem-based approach (EBA). Today, it is crucial that indicators and assessment systems follow this vision [@berg-2015].

# How to develop an indicator

Developing indicators is no longer an isolated exercise but needs to be embedded into the overall approach. Indicators typically need to answer management questions. The first question a manager will ask is:

> Do I need to take action or not?

Given a certain assessment based on one or more indicators, the next question will often be something about the quality of the assessment:

> How sure are you about your results?

Science tends to follow a bottom-up approach, starting with isolated indicator development and only caring for the integrative nature of the assessment or the actual requirements of the legal framework at a late stage. To successfully make indicators fit for purpose, a top-down approach should be used. Deriving the cornerstones of an indicator from the requirements of policy and legislation ensures that it fits into the overall assessment system and enhances its acceptance. To this end, a close cooperation with the responsible organizations is vital, ideally involving them in the development process. This also enables science to provide early feedback and advice to stakeholders, working towards consistency between societal demands, the corresponding scientific knowledge and the actual implementation of policies in a complex reality.

## Scope

This involves being clear about the scope of the indicator. If the framework, the indicator is developed for, is a part of a larger set of indicators, it is crucial to avoid a thematic overlap with related indicators within the same framework. An example: In a set of biodiversity indicators, you want to avoid that most of them deal with the same well-known ecosystem components (mostly phytoplankton, benthos, fish, birds and mammals). Having many different indicators on well-known and often charismatic organisms, and at the same time lacking indicators for bacterica, zooplankton, biotopes and others, will in most cases lead to a biased view on the ecosystem and as such result in a skewed assessment.

## Know the place within the management cycle

It must be decided which stage the indicator is representing in the management cycle. A typical management cycle is the DPSIR approach, recently expanded to DAPSI(W)R(M) [see e.g. @elliott-2002; elliott-2017]. This framework is a problem-structuring approach used to clearly show the different stages of environmental management. The idea is to distinguish between societal drivers (D) that give rise to human activities (A). These activities lead to pressues (P) on the natural system (the ecosystem). This, in turn, results in state changes (S) within the natural system. Such changes will eventually be followed by impacts (I) on welfare (W). The subsequent social reaction will be a management response (R) in terms of measures (M) to be take in order to change the situation for the better. An example for such a cycle is fishery:

* Driver: human request for food, especially sea food
* Activity: fishing boats are built and begin fishing
* Pressure: Fishing results in many pressures such as removal of fish from the natural system, physical disturbance of the sea floor
* State change: e.g. an altered population structure of fish populations, having further effects on the whole ecosystem
* Impact: e.g. fish gets expensive when there is less fish and still high demand
* Response: e.g. fishing quotas, ocean reserves, regulation of gear and area/time of allowd fishing

Indicators, telling management about the status of each of these stages, need to be specifically designed around the stage they want to indicate. As an example, pressure indicators aim to measure the magnitude of anthropogenic pressures and thus potentially control their societal drivers. This is a quite strong management response. State indicators will describe and assess the environmental state as a result of these pressures. This can lead to weaker management responses in terms of trying to conserve a certain state (this is the typical field of nature conservation).

## Target ecosystem component

Ecosystems consist of various parts. In general, ecosystems can be divided into their structure (abiotic habitat, biotic biocoenisis, resulting biotopes) and their functions (food webs, flow of matter and energy, cycles of carbon and nutrients, ...). The indicator should focus on a specific part of the ecosystem. This will allow to interpret the meaning of the indicator value and substantiate which measures to take in order to improve the overall ecosystem health.

## Connection to measures
...

## Implementation details

Depending on the knowledge about the system to indicate and the goal to reach, an indicator can have various forms. For some aspects, it is only relevant to know a trend (such as increasing or decreasing pressure). This is typically the case when no threshold values for good status are defined. Other indicators may need several individual metrics which are calculated together (so-called multi-metric indicators) in order to give a meaningful result. Also, the scale in terms of time and space is important. Does the indicator need time series data? Is it applicable to various spatial scales and does it scale properly along the spatial and temporal dimensions?

In the end, a specific algorithm or formula will be applied in order to derive the indicator value. This algorithm/formula needs to be very carefully aligned to the requirements of the legal framework in which the indicator needs to work. Typically, you need to pay attention to numerical scale, threshold/target values and reference values. Last, but not least, you will want to follow rules for a “good indicator” [e.g. @queiros-2016]

## Uncertainty

Another important aspect is uncertainty. Build uncertainty into your indicator right from the start. Typically, people overestimate the certainty of their results. Having a measure of uncertainty not only helps to discard a bad indicator (one that doesn't actually indicate anything given some nasty uncertainties) and detect a good one, but also helps managers to decide. A rule may be that managers will not take actions when there isn't enough proof for a specific claim an indicator makes. Or they may be precautionary and knowing about the uncertainty of an indicator values helps to take the right actions. In the end, it also helps the scientists being honest about the limits of their statement given poor data coverage and many constraints under which managers request exact answers that scientiests not can give.

# How to develop an assessment system

- Science does not define thresholds, but policy does (however, science interprets and sets them)
- Make a rough cur first (deploy early and often), refine later (management cycles)
- The more modular, the better (not just one large convoluted formula)
- Make it easy to use and easy to share


# What is ecosystem health?
Ecosystem health is a human in invention ...

# Notes, to be incorporated into the text:

- Legal frameworks tend to be poorly defined
- Managers want clear answers, scientists don’t give them
- Some indicators are designed to understand natural systems, not to assess them

- Stick to best practices and given frameworks
- Include uncertainty from the start
- Science can influence how the next management frameworks and decisions will look like
- Have a Man-in-the-Middle knowing both worlds
