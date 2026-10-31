
<div align="center">

# Geographic Information System for Drug Case Mapping

### Spatial Analysis and Administrative Boundary Identification Using the Ray Casting Algorithm

**West Kalimantan, Indonesia · 2025**

A web-based Geographic Information System (GIS) designed to support
the visualization, management, and spatial analysis of drug-related
case records using the Ray Casting algorithm.

The application integrates interactive geographic mapping,
administrative boundary identification, case reporting,
and centralized data management to support location-based
analysis and structured information reporting.

**Laravel 12** &nbsp;·&nbsp; **PHP** &nbsp;·&nbsp; **MySQL** &nbsp;·&nbsp; **Leaflet.js** &nbsp;·&nbsp; **Bootstrap 5** &nbsp;·&nbsp; **Ray Casting**

<br>

[Overview](#overview) &nbsp;·&nbsp;
[Application](#application-showcase) &nbsp;·&nbsp;
[Methodology](#spatial-analysis-methodology) &nbsp;·&nbsp;
[Technology](#technology-stack) &nbsp;·&nbsp;
[Developer](#developer)

</div>

---

## Overview

Geographic Information Systems provide an important foundation
for understanding the spatial distribution of events and
supporting location-based analysis.

In drug-related case monitoring, geographic information
can help identify the administrative areas associated
with reported incidents and facilitate the visualization
of spatial patterns.

This project develops a web-based **Geographic Information
System for Drug Case Mapping** using Laravel 12
and the Ray Casting algorithm.

The application focuses on mapping and managing
drug-related case records across **West Kalimantan, Indonesia**.

The Ray Casting algorithm is applied to determine whether
a geographic coordinate falls within a specific
administrative boundary represented by a polygon.

By integrating geospatial processing with an interactive
web interface, the application provides a structured
environment for case management, geographic analysis,
and administrative reporting.

Although the initial implementation focuses on West Kalimantan,
the underlying spatial approach can be adapted to other
regions of Indonesia when appropriate geographic boundaries
and supporting data are available.

### Project at a Glance

| | |
|:---|:---|
| **Project** | Geographic Information System for Drug Case Mapping |
| **Study Area** | West Kalimantan, Indonesia |
| **Geographic Scope** | Districts and Municipalities |
| **Application Type** | Web-Based Geographic Information System |
| **Primary Algorithm** | Ray Casting |
| **Spatial Operation** | Point-in-Polygon Identification |
| **Geographic Representation** | Coordinates and Administrative Polygons |
| **Backend Framework** | Laravel 12 |
| **Database** | MySQL |
| **Mapping Library** | Leaflet.js |
| **Frontend Framework** | Bootstrap 5 |
| **Developer** | Roni, S.Kom. |
| **Development Year** | 2025 |

---

## Application Showcase

The application provides an integrated environment
for displaying geographic information, managing case records,
performing spatial analysis, and generating reports.

Its interface consists of public-facing pages
and administrative modules.

### 01 / Homepage

**Geographic information and public access.**

The homepage serves as the primary entry point
to the Geographic Information System.

It introduces the application and provides access
to the available public-facing features.

The interface is designed to make geographic
information and system navigation accessible
through a responsive web environment.

<p align="center">
  <img src="screenshots-website/1-HomePage.png"
       alt="GIS Homepage"
       width="100%">
</p>

<p align="center"><sub>Figure 01 — Geographic Information System Homepage</sub></p>

<br>

### 02 / Case Reporting Interface

**Structured geographic case reporting.**

The reporting interface provides a form
for entering information related to reported cases.

The submitted information can serve as an input
for administrative review and subsequent
geographic data processing.

This module supports a more organized approach
to collecting location-based case information.

<p align="center">
  <img src="screenshots-website/2-ReportForm.jpg"
       alt="Case Reporting Form"
       width="100%">
</p>

<p align="center"><sub>Figure 02 — Case Reporting Interface</sub></p>

<br>

### 03 / Administrator Authentication

**Controlled access to administrative features.**

The administrator login interface provides
an authentication entry point for accessing
the application's management environment.

Administrative functions are organized separately
from the public-facing application interface.

<p align="center">
  <img src="screenshots-website/3-LoginAdmin.jpg"
       alt="Administrator Login"
       width="100%">
</p>

<p align="center"><sub>Figure 03 — Administrator Authentication</sub></p>

<br>

### 04 / Administrative Dashboard

**Centralized geographic case management.**

The dashboard serves as the main workspace
for accessing administrative features,
case information, spatial analysis,
and reporting modules.

It provides a centralized interface
for managing application operations
and navigating geographic information.

<p align="center">
  <img src="screenshots-website/4-AdminDashboard.jpg"
       alt="Administrative Dashboard"
       width="100%">
</p>

<p align="center"><sub>Figure 04 — Administrative Dashboard</sub></p>

<br>

### 05 / Case Data Management

**Organized management of geographic case records.**

The case management module provides
a structured interface for maintaining
drug-related case information.

The module includes interfaces for:

- Viewing recorded cases
- Inspecting individual case details
- Updating existing case information
- Entering new case records
- Managing geographic case attributes

<p align="center">
  <img src="screenshots-website/5-DataKasus.jpg"
       alt="Case Data Management"
       width="100%">
</p>

<p align="center"><sub>Figure 05 — Geographic Case Data Management</sub></p>

<details>
<summary>View additional case management screenshots</summary>

<br>

**Case Details**

![Case Details](screenshots-website/6-DetailKasus.jpg)

**Edit Case**

![Edit Case](screenshots-website/7-EditKasus.jpg)

</details>

<br>

### 06 / Multi-Step Case Registration

**Structured data entry through a guided workflow.**

The case registration process is organized
into four sequential stages.

This approach divides data entry
into manageable steps and supports
consistent case information recording.

The multi-step interface provides
a structured workflow for preparing
new case records.

<p align="center">
  <img src="screenshots-website/8-CreateDataStep1.jpg"
       alt="Case Registration Step 1"
       width="100%">
</p>

<p align="center"><sub>Figure 06 — Case Registration Workflow</sub></p>

<details>
<summary>View additional case registration steps</summary>

<br>

**Step 2 — Case Registration**

![Case Registration Step 2](screenshots-website/9-CreateDataStep2.jpg)

**Step 3 — Case Registration**

![Case Registration Step 3](screenshots-website/10-CreateDataStep3.jpg)

**Step 4 — Case Registration**

![Case Registration Step 4](screenshots-website/11-CreateDataStep4.jpg)

</details>

<br>

### 07 / Spatial Analysis Dashboard

**Exploring geographic case information.**

The spatial analysis module provides
an interface for examining geographic
information associated with recorded cases.

It supports the organization and interpretation
of case locations within administrative areas.

The geographic analysis workflow connects
case coordinates with administrative boundaries
to provide a spatial perspective
on recorded incidents.

<p align="center">
  <img src="screenshots-website/12-AnalisisIndex.jpg"
       alt="Spatial Analysis Dashboard"
       width="100%">
</p>

<p align="center"><sub>Figure 07 — Spatial Analysis Dashboard</sub></p>

<br>

### 08 / Ray Casting Geographic Mapping

**Administrative boundary identification using spatial geometry.**

The mapping module integrates the Ray Casting
algorithm with geographic information
and interactive map visualization.

Ray Casting is used to evaluate
whether a coordinate lies within
a predefined administrative polygon.

This enables the system to associate
case locations with corresponding
district or municipality boundaries.

The interactive map provides
a visual representation of the spatial
relationship between geographic coordinates
and administrative regions.

<p align="center">
  <img src="screenshots-website/13-RayCastingPeta.jpg"
       alt="Ray Casting Geographic Mapping"
       width="100%">
</p>

<p align="center"><sub>Figure 08 — Ray Casting on Geographic Map</sub></p>

<br>

### 09 / Algorithm Analysis

**Understanding spatial classification results.**

The algorithm analysis interface
provides a dedicated environment
for examining the spatial processing
performed by the application.

It supports the interpretation
of coordinate-based geographic
classification using Ray Casting.

This module demonstrates how
computational geometry can be applied
to administrative boundary identification.

<p align="center">
  <img src="screenshots-website/14-AnalisisAlgoritma.jpg"
       alt="Ray Casting Algorithm Analysis"
       width="100%">
</p>

<p align="center"><sub>Figure 09 — Ray Casting Algorithm Analysis</sub></p>

<br>

### 10 / Geographic Case Reporting

**Structured information for administrative review.**

The reporting module organizes
case information into a structured
interface for review and documentation.

It provides access to recorded case
information and individual report details.

This module supports administrative
documentation and the presentation
of geographic case information.

<p align="center">
  <img src="screenshots-website/15-Laporan.jpg"
       alt="Case Reporting Dashboard"
       width="100%">
</p>

<p align="center"><sub>Figure 10 — Geographic Case Reporting</sub></p>

<details>
<summary>View report details</summary>

<br>

**Detailed Report**

![Detailed Report](screenshots-website/16-DetailLaporan.jpg)

</details>

<br>

### 11 / Administrator Profile

**Administrative account information management.**

The administrator profile module
provides an interface for updating
account information within the
application management environment.

<p align="center">
  <img src="screenshots-website/17-EditProfileAdmin.jpg"
       alt="Administrator Profile Management"
       width="100%">
</p>

<p align="center"><sub>Figure 11 — Administrator Profile Management</sub></p>

---

## Spatial Analysis Methodology

### Research and Development Approach

The application follows a structured
geographic information processing workflow,
from case data collection to
spatial visualization and reporting.

**Data Collection → Coordinate Acquisition → Geographic Boundary Preparation → Ray Casting → Spatial Classification → Map Visualization → Reporting**

### Geographic Data

The spatial analysis process involves
several interconnected types of information.

| Data Component | Description |
|:---|:---|
| Case Records | Information associated with reported cases |
| Latitude | Geographic north-south coordinate |
| Longitude | Geographic east-west coordinate |
| Administrative Boundaries | Geographic polygons representing regional areas |
| District / Municipality | Administrative unit associated with a geographic location |
| Spatial Classification | Result of point-in-polygon evaluation |
| Geographic Visualization | Map representation of case locations and boundaries |

The case coordinates serve as spatial input,
while administrative polygons define
the geographic regions being evaluated.

### Ray Casting Algorithm

The **Ray Casting algorithm** is a computational
geometry technique used to determine
whether a point lies inside or outside
a polygon.

The algorithm is commonly applied
to point-in-polygon problems in
geographic information processing.

In this application, Ray Casting
is used to identify the administrative
region containing a reported case location.

### Point-in-Polygon Principle

The algorithm works by extending
an imaginary ray from a geographic point
and counting its intersections
with the polygon boundaries.

The general rule is:

- An odd number of intersections indicates that the point is inside the polygon.
- An even number of intersections indicates that the point is outside the polygon.
- Points located exactly on polygon boundaries require explicit boundary-handling rules.

This principle enables the classification
of geographic coordinates relative
to administrative boundaries.

### Algorithm Workflow

**1. Coordinate Input**

The application obtains the latitude
and longitude associated with a
case location.

**2. Administrative Polygon Retrieval**

The system identifies the relevant
administrative boundary geometries
for spatial evaluation.

**3. Ray Construction**

An imaginary horizontal ray
is extended from the input point.

**4. Boundary Intersection Testing**

The algorithm evaluates intersections
between the ray and the polygon edges.

**5. Intersection Counting**

The total number of valid intersections
is calculated.

**6. Spatial Classification**

The point is classified as being
inside or outside the evaluated polygon.

**7. Administrative Region Identification**

When a matching polygon is identified,
the corresponding administrative region
can be associated with the case record.

### Geographic Classification Example

Consider a reported case represented
by geographic coordinates.

The system evaluates the point
against available district and
municipality polygons.

If the point is determined to be
inside a particular administrative polygon,
the application can associate the
case location with that region.

This process reduces the need
for manually identifying administrative
areas from coordinate information.

### Spatial Processing Considerations

Accurate geographic identification
depends on several factors:

- Coordinate precision and validity
- Consistent geographic coordinate reference systems
- Administrative boundary data quality
- Correct polygon geometry
- Polygon edge and vertex handling
- Multipolygon and boundary intersection cases

The Ray Casting method determines
geometric containment.

It does not independently verify
the correctness of reported case
coordinates or administrative datasets.

---

## System Architecture

### Application Components

The application integrates
web-based administration,
database management,
geographic visualization,
and spatial processing.

| Component | Responsibility |
|:---|:---|
| Web Interface | User interaction and application navigation |
| Laravel Backend | Application logic and server-side processing |
| MySQL Database | Structured application data storage |
| Leaflet.js | Interactive geographic visualization |
| Administrative Area API | Supporting geographic region information |
| Ray Casting Algorithm | Point-in-polygon spatial classification |
| Reporting Module | Case information presentation and documentation |

### Processing Architecture

The general processing flow is:

**User Input → Laravel Application → MySQL Database → Spatial Processing → Administrative Classification → Geographic Visualization**

The application combines conventional
web information system functionality
with geometric algorithms for
location-based analysis.

---

## Application Capabilities

### Geographic Information Management

The application supports location-based
information handling within an
interactive geographic environment.

### Administrative Area Identification

The Ray Casting algorithm provides
a geometric approach for associating
case coordinates with administrative polygons.

### Centralized Case Management

Administrative modules provide
structured interfaces for maintaining
case information and associated records.

### Interactive Map Visualization

Leaflet.js enables geographic
information to be displayed
through an interactive web map.

### Reporting and Documentation

The reporting module supports
the structured presentation
and review of recorded case information.

### Regional Adaptability

The geographic processing approach
is not conceptually limited to West Kalimantan.

With appropriate administrative boundary
datasets, coordinate information,
and application configuration,
it can be adapted to other geographic
areas, including broader Indonesian regions.

This adaptability does not imply
that nationwide deployment
has already been tested.

---

## Technology Stack

| Layer | Technologies |
|:---|:---|
| Backend Framework | Laravel 12 |
| Programming Language | PHP 8+ |
| Database | MySQL |
| Frontend | HTML, CSS, JavaScript |
| UI Framework | Bootstrap 5 |
| Admin Template | Stisla |
| Interactive Mapping | Leaflet.js |
| Spatial Algorithm | Ray Casting |
| Geographic Integration | Indonesian Administrative Area API |
| Spatial Analysis | Point-in-Polygon |
| Application Type | Web-Based Geographic Information System |

---

## Scope and Limitations

The application is developed
as a geographic information system
for spatial case mapping
and administrative data management.

Its initial geographic scope
focuses on West Kalimantan, Indonesia.

The Ray Casting algorithm operates
on geographic coordinates
and polygon boundary representations.

Its classification results depend
on the validity of coordinate inputs
and the accuracy of the administrative
boundary data.

The application is intended
for research, educational,
and geographic information
management purposes.

Spatial distributions should not
be interpreted as direct measures
of drug prevalence or geographic risk
without considering reporting coverage,
population differences,
and data collection limitations.

### Data Privacy

Drug-related case information
may contain sensitive personal
or location-based data.

Any public demonstration
or publication of case records
should use appropriately anonymized
or aggregated information.

Access to personally identifiable
information should be restricted
to authorized users.

---

## Future Development

Potential areas for future
development include:

- Alternative point-in-polygon algorithms
- Comparative evaluation of spatial algorithms
- Improved geographic boundary validation
- Extended geographic coverage across Indonesia
- Enhanced spatial filtering and analysis
- Statistical visualization of case distributions
- Optimized processing of large polygon datasets
- Additional privacy and access-control safeguards

These improvements represent
potential development directions
rather than currently verified features.

---

## Repository Scope

This repository serves as a
**public-facing GIS and software
development portfolio**.

It presents the application's
interface documentation,
geographic processing concepts,
system architecture,
and implementation technologies.

The repository includes:

- Application screenshots
- GIS functionality documentation
- Ray Casting methodology
- Spatial analysis overview
- Technology stack information
- System capability descriptions

The complete source code,
database configuration,
and application resources
are maintained separately
and are not publicly distributed
through this repository.

### Source Code Access

For inquiries regarding
application source code,
technical information,
or development collaboration,
please contact:

**Developer:** Roni, S.Kom.

**WhatsApp:** [+62 858-4960-4654](https://wa.me/6285849604654)

**Email:** [ronn.7ex@gmail.com](mailto:ronn.7ex@gmail.com)

---

## Developer

**Roni, S.Kom.**

Software Engineering · Geographic Information Systems ·
Spatial Analysis · Web Development

West Kalimantan, Indonesia

This project represents the development
of a web-based Geographic Information System
integrating spatial algorithms
with modern web technologies.

---

<div align="center">

<sub>Geographic Information System for Drug Case Mapping</sub>

<br>

<sub>Ray Casting Algorithm · West Kalimantan, Indonesia</sub>

<br>

<sub>Software Development & GIS Portfolio — Roni, S.Kom. · 2025</sub>

<br>

<sub>All Rights Reserved.</sub>

</div>
