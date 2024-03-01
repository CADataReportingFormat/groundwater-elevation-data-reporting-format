# Well Characteristics Reporting Format Terminology

[Local Well Name](#local-well-name) | [State Well Number](#state-well-number) | [Site Code](#site-code) | [Permit Number](#permit-number) | [Local Permit Agency](#local-permit-agency) | [Latitude](#latitude) | [Longitude](#longitude) | [Coordinates Survey Date](#coordinates-survey-date) | [Coordinates Survey Time](#coordinates-survey-time) | [Coordinates Datum](#coordinates-datum) | [Coordinates Method](#coordinates-method) | [Coordinates Accuracy](#coordinates-accuracy) | [Coordinates Surveyor](#coordinates-surveyor) | [Coordinates Equipment](#coordinates-equipment) | [Coordinates Survey Field Notes](#coordinates-survey-field-notes) | [Reference Point Elevation (RPE)](#reference-point-elevation-(rpe)) | [Ground Surface Elevation (GSE)](#ground-surface-elevation-(gse)) | [Elevation Survey Date](#elevation-survey-date) | [Elevation Survey Time](#elevation-survey-time) | [Elevation Measurement Method](#elevation-measurement-method) | [Elevation Vertical Datum](#elevation-vertical-datum) | [Elevation Accuracy](#elevation-accuracy) | [Elevation Surveyor Name](#elevation-surveyor-name) | [Elevation Survey Field Notes](#elevation-survey-field-notes) | [Well Riser Height (RHT)](#well-riser-height-(rht)) | [Total Well Depth](#total-well-depth) | [Type of Opening](#type-of-opening) | [Depth to Top of Screen (1)...(10)](#depth-to-top-of-screen-(1)...(10)) | [Depth to Bottom of Screen (1)...(10)](#depth-to-bottom-of-screen-(1)...(10)) | [Well Casing Material](#well-casing-material) | [Well Casing Diameter](#well-casing-diameter) | [Well Slot Size](#well-slot-size) | [Well Status](#well-status) | [Well Use Type](#well-use-type) | [Well Completion Structure](#well-completion-structure) | [Well Completion Report Number](#well-completion-report-number) | [Well Completion Date](#well-completion-date) | [Well Location Description](#well-location-description) | [SGMA Monitoring Network](#sgma-monitoring-network) | [Additional Comments](#additional-comments) | 

### Local Well Name
|**Attribute**|Local Well Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Name or number identifier given by the Monitoring Agency used to identify the well on a local basis.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### State Well Number
|**Attribute**|State Well Number|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|State Well Number provided by the Department of Water Resources.|
|**Required/Optional**|At least one well identifier must be entered for each submittal|
|**Unit/Format**|N/A|

### Site Code
|**Attribute**|Site Code|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Unique identifier assigned to each well for a relevant program that the program uses to track individual wells within the program's system.|
|**Required/Optional**|At least one well identifier must be entered for each submittal|
|**Unit/Format**|N/A|

### Permit Number
|**Attribute**|Permit Number|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Permitting agency permit number associated with well.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Local Permit Agency
|**Attribute**|Local Permit Agency|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Agency who approved permit associated with well.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Latitude
|**Attribute**|Latitude|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Latitude of the well location (Y Coordinate).|
|**Required/Optional**|Required|
|**Unit/Format**|Decimal degrees|

### Longitude
|**Attribute**|Longitude|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Longitude of the well location (X Coordinate).|
|**Required/Optional**|Required|
|**Unit/Format**|Decimal degrees|

### Coordinates Survey Date
|**Attribute**|Coordinates Survey Date|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Date that the XY coordinates of the well were surveyed.|
|**Required/Optional**|Optional|
|**Unit/Format**|mm/dd/yyyy|

### Coordinates Survey Time
|**Attribute**|Coordinates Survey Time|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Time that the XY coordinates of the well were surveyed.|
|**Required/Optional**|Optional, default is 12:00:00|
|**Unit/Format**|hh:mm:ss (PST 24-hour)|

### Coordinates Datum
|**Attribute**|Coordinates Datum|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Horizontal datum associated with Latitude and Longitude measurement.|
|**Required/Optional**|Optional|
|**Unit/Format**|NAD83 (recommended)|

### Coordinates Method
|**Attribute**|Coordinates Method|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Method used to determine latitude and longitude of well location.|
|**Required/Optional**|Required|
|**Unit/Format**|Description of method used|

### Coordinates Accuracy
|**Attribute**|Coordinates Accuracy|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Accuracy of well location latitude and longitude measurements.|
|**Required/Optional**|Optional|
|**Unit/Format**|feet|

### Coordinates Surveyor
|**Attribute**|Coordinates Surveyor|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|The full names of the organization and surveyor who collected the latitude/longitude coordinates.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Coordinates Equipment
|**Attribute**|Coordinates Equipment|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|The name or type of GPS equipment and model number used to collect the latitude/longitude coordinates.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Coordinates Survey Field Notes
|**Attribute**|Coordinates Survey Field Notes|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Any additional notes from the field during coordinates survey.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Reference Point Elevation (RPE)
|**Attribute**|Reference Point Elevation (RPE)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Elevation of the reference point from which depth to water measurements are collected.|
|**Required/Optional**|Required|
|**Unit/Format**|feet |

### Ground Surface Elevation (GSE)
|**Attribute**|Ground Surface Elevation (GSE)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Elevation of the ground surface associated with the location of the well.|
|**Required/Optional**|Optional|
|**Unit/Format**|feet|

### Elevation Survey Date
|**Attribute**|Elevation Survey Date|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Date that the reference point elevation and/or ground surface elevation was surveyed.|
|**Required/Optional**|Optional|
|**Unit/Format**|mm/dd/yyyy|

### Elevation Survey Time
|**Attribute**|Elevation Survey Time|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Time that the reference point elevation and/or ground surface elevation was surveyed.|
|**Required/Optional**|Optional, default is 12:00:00|
|**Unit/Format**|hh:mm:ss (PST 24-hour)|

### Elevation Measurement Method
|**Attribute**|Elevation Measurement Method|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Method used to survey elevations.|
|**Required/Optional**|Optional|
|**Unit/Format**|Description of method used|

### Elevation Vertical Datum
|**Attribute**|Elevation Vertical Datum|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Vertical datum associated with elevation measurements.|
|**Required/Optional**|Required|
|**Unit/Format**|NAVD88 (recommended)|

### Elevation Accuracy
|**Attribute**|Elevation Accuracy|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Accuracy of elevation measurements.|
|**Required/Optional**|Optional|
|**Unit/Format**|feet|

### Elevation Surveyor Name
|**Attribute**|Elevation Surveyor Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|The name of the organization collecting the elevation measurements.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Elevation Survey Field Notes
|**Attribute**|Elevation Survey Field Notes|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Any additional notes from the field during elevation survey.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Well Riser Height (RHT)
|**Attribute**|Well Riser Height (RHT)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Measured distance from ground surface to top of well casing.|
|**Required/Optional**|Optional|
|**Unit/Format**|feet|

### Total Well Depth
|**Attribute**|Total Well Depth|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Depth to the bottom of the well below ground surface.|
|**Required/Optional**|Required|
|**Unit/Format**|feet below GSE|

### Type of Opening
|**Attribute**|Type of Opening|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|How water enters the well from the aquifer. Most drilling methods use a well screen while cable tooled wells may use an open hole. |
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Depth to Top of Screen (1)...(10)
|**Attribute**|Depth to Top of Screen (1)...(10)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Depth to the top of a screened interval below ground surface. Can include up to 10 different screened intervals.|
|**Required/Optional**|Required|
|**Unit/Format**|feet below GSE|

### Depth to Bottom of Screen (1)...(10)
|**Attribute**|Depth to Bottom of Screen (1)...(10)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Depth to the bottom of a screened interval below ground surface. Can include up to 10 different screened intervals.|
|**Required/Optional**|Required|
|**Unit/Format**|feet below GSE|

### Well Casing Material
|**Attribute**|Well Casing Material|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Material that the well casing is made from.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Well Casing Diameter
|**Attribute**|Well Casing Diameter|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Inside diameter of the well casing.|
|**Required/Optional**|Optional|
|**Unit/Format**|inches|

### Well Slot Size
|**Attribute**|Well Slot Size|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Size of well screen individual perforations, or slots, or the mesh size of the screen.|
|**Required/Optional**|Optional|
|**Unit/Format**|inches|

### Well Status
|**Attribute**|Well Status|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Status of the well.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Well Use Type
|**Attribute**|Well Use Type|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Primary use of the well.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Well Completion Structure
|**Attribute**|Well Completion Structure|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Description of well completion structure.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Well Completion Report Number
|**Attribute**|Well Completion Report Number|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|The Department of Water Resources Well Completion Report Number (OSWCR Legacy Log Number).|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Well Completion Date
|**Attribute**|Well Completion Date|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Date that the well was completed.|
|**Required/Optional**|Optional|
|**Unit/Format**|mm/dd/yyyy|

### Well Location Description
|**Attribute**|Well Location Description|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Description of the location of the well and any other notes used to identify the well's location.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### SGMA Monitoring Network
|**Attribute**|SGMA Monitoring Network|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|The monitoring network that the well is associated with under a Groundwater Sustainability Plan.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Additional Comments
|**Attribute**|Additional Comments|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Any additional comments concerning well characteristics.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

