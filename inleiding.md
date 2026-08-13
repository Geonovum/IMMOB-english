# Introduction

## About this document

This document is a shortened version of the original IMMOB document describing the Informationmodel Mobility. This document concentrates only on the IMMOB - UML and objectcataloque. It is created as an English version of the original Dutch model. It originates from same UML - model and is generated on the basis of added alias items in English to all element names. The IMMOB UML model in that sens is made bi-lingual.

## General introduction
The Ministry of Infrastructure and Water Management (IenW) has requested the National Access Point for Mobility Data (NTM) to develop an initial version of the Mobility Data Catalogue. This catalogue constitutes an important building block within the Digital System for Mobility Data (DSM), where data from various sources are brought together to organize mobility in a smarter, more efficient, and more sustainable way.

The development of the data catalogue takes place in close alignment with the transposition process of the European ITS Directive (Intelligent Transport Systems). This directive requires Member States to make specific mobility data available, and its translation into the Dutch context is currently underway. Coordination with this process is essential to ensure consistent implementation.

## Purpose and Function of the Data Catalogue

The purpose of the Mobility Data Catalogue is to describe datasets that fall within the scope of the DSM in a uniform and standardized manner. This includes information on definitions, quality, scope of application, obligations, and responsible parties. By documenting this information in a standardized way, the catalogue provides clarity to data providers, supervisory authorities, and users regarding which data are required, under what conditions, and who is responsible for what.

In the future, the data catalogue will be linked to NTM’s national mobility data register. This will provide insight into the availability and progress of datasets and enable targeted support where necessary. During this phase, the temporary DSM data table serves as an interim solution until the data catalogue becomes operational.

data/Images/Gegevenscatalogus_in_context.png Architecture diagram of the data catalogue in the context of legislation and implementation
From Prototype to Standard

Within this project, an initial prototype of the data catalogue will be developed, focusing on a limited number of selected datasets covered by the ITS Directive. At the same time, the initial design will be evaluated to determine whether it is suitable for further development into a fully-fledged, scalable, and secure solution.

## Concepts and Models

In addition to dataset descriptions, the data catalogue will include a conceptual framework for the mobility data domain. This consists of:

A concept model in accordance with the Dutch NL-SBB standard [[NL-SBB]] (MIM level 1);

A conceptual information model compliant with MIM [[MIM12]] (MIM level 2);

The actual data catalogue, in which dataset-specific information is recorded, including:

What: Definitions and quality agreements;
Why: Legal basis or DSM agreement;
Where: Geographical scope (routes, junctions, areas);
When: Timeframes and compliance deadlines;
Who must: Responsible data provider;
Who decides: Governance arrangements;
How: National facility or service.

## Scope

The scope of the conceptual schema is Mobility data. Mobility data encompasses all information relevant to optimizing the transport of people and goods. This ranges from static data about infrastructure to dynamic, real-time data on traffic flows, congestion, or road closures. The data catalogue is aligned with developments in the European Mobility Data Space initiative, in which mobility data is considered a critical resource for innovation and service provision.

## Design Principles

The Mobility Data Catalogue is a core instrument within the Digital System for Mobility Data (DSM) and serves as the bridge between legal concepts derived from legislation and regulations and information management concepts used in mobility datasets. This data catalogue forms part of the broader Mobility Data Catalogue and focuses on data types relating to real-time traffic information for Intelligent Transport Systems (ITS).

At the heart of this data catalogue is a centrally managed conceptual schema. This conceptual schema serves as the single source of truth in which all relevant knowledge, including legal concepts, datasets, relationships, and sources, is brought together.

The conceptual schema has been designed to establish an unambiguous connection between formal legal terminology and the concepts defined in the European ITS Directive (http://data.europa.eu/eli/dir/2010/40/2023-12-20) and the associated delegated regulations:

[Real-Time Traffic Information (RTTI)](https://eur-lex.europa.eu/eli/reg_del/2022/670/oj)

[Multimodal Travel Information Services (MMTIS)](http://data.europa.eu/eli/reg_del/2024/490/oj)

[Safety-Related Traffic Information (SRTI)](http://data.europa.eu/eli/reg_del/2013/886/oj)

[Safe and Secure Truck Parking (SSTP)](http://data.europa.eu/eli/reg_del/2013/885/oj)

The model further connects these legal concepts to information management concepts used in Dutch mobility datasets. As a result, it provides a shared, consistent, and reliable conceptual framework that can be used by policymakers, data providers, implementers, and users alike.
