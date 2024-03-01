# Groundwater Elevation Reporting Format Terminology

[Local Well Name](#local-well-name) | [State Well Number](#state-well-number) | [Site Code](#site-code) | [Relevant Program](#relevant-program) | [Permit Number](#permit-number) | [Local Permit Agency](#local-permit-agency) | [Measurement Date](#measurement-date) | [Measurement Time](#measurement-time) | [Reading at Reference Point (RRP)](#reading-at-reference-point-(rrp)) | [Reading at Water Surface (RWS)](#reading-at-water-surface-(rws)) | [Water Surface Elevation (WSE)](#water-surface-elevation-(wse)) | [Ground Surface to Water Surface (GS to WS)](#ground-surface-to-water-surface-(gs-to-ws)) | [Water Level Datum](#water-level-datum) | [No Measurement Code](#no-measurement-code) | [Measurement Quality Code](#measurement-quality-code) | [Measurement Method](#measurement-method) | [Measurement Accuracy](#measurement-accuracy) | [Collection Agency](#collection-agency) | [Reporting Agency](#reporting-agency) | [Water Level Comments](#water-level-comments) | 

### Local Well Name
|**Attribute Name**|Local Well Name|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Name or number identifier given by the Monitoring Agency used to identify the well on a local basis.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### State Well Number
|**Attribute Name**|State Well Number|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|State Well Number provided by the Department of Water Resources.|
|**Required/Optional**|At least one well identifier must be entered for each submittal|
|**Unit/Format**|N/A|

### Site Code
|**Attribute Name**|Site Code|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Unique identifier assigned to each well for a relevant program that the program uses to track individual wells within the program's system.|
|**Required/Optional**|At least one well identifier must be entered for each submittal|
|**Unit/Format**|N/A|

### Relevant Program
|**Attribute Name**|Relevant Program|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Name of the program that the Master Code has been specified from to aid in identifying what program the well is associated with.|
|**Required/Optional**|Required; if Site Code entered |
|**Unit/Format**|N/A|

### Permit Number
|**Attribute Name**|Permit Number|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Permitting agency permit number associated with well.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Local Permit Agency
|**Attribute Name**|Local Permit Agency|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Agency who approved permit associated with well.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Measurement Date
|**Attribute Name**|Measurement Date|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Date groundwater level measurement was taken.|
|**Required/Optional**|Required|
|**Unit/Format**|mm/dd/yyyy|

### Measurement Time
|**Attribute Name**|Measurement Time|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Time groundwater level measurement was taken.|
|**Required/Optional**|Optional; default is 12:00:00|
|**Unit/Format**|hh:mm:ss (PST 24-hour)|

### Reading at Reference Point (RRP)
|**Attribute Name**|Reading at Reference Point (RRP)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Reading of the measurement device taken at the reference point of the well.|
|**Required/Optional**|Required; unless a No Measurement Code is selected|
|**Unit/Format**|feet below RP|

### Reading at Water Surface (RWS)
|**Attribute Name**|Reading at Water Surface (RWS)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Measurement of the watermark on a steel tape, equivalent, or electronic sounder after making the groundwater sounding; typically 0.00 for an electronic sounder.|
|**Required/Optional**|Optional; default is 0.00|
|**Unit/Format**|feet|

### Water Surface Elevation (WSE)
|**Attribute Name**|Water Surface Elevation (WSE)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Calculated water surface elevation.|
|**Required/Optional**|Optional|
|**Unit/Format**|feet; default in NAVD88|

### Ground Surface to Water Surface (GS to WS)
|**Attribute Name**|Ground Surface to Water Surface (GS to WS)|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Depth to water below ground surface.|
|**Required/Optional**|Optional|
|**Unit/Format**|feet below ground surface (bgs)|

### Water Level Datum
|**Attribute Name**|Water Level Datum|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Vertical datum associated with calculated water surface elevation.|
|**Required/Optional**|Required|
|**Unit/Format**|NAVD88 (recommended)|

### No Measurement Code
|**Attribute Name**|No Measurement Code|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Code providing explanation for no groundwater level measurement being taken.|
|**Required/Optional**|Required; unless a RRP is entered|
|**Unit/Format**|N/A|

### Measurement Quality Code
|**Attribute Name**|Measurement Quality Code|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Code providing a description of the quality of the groundwater level measurement.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Measurement Method
|**Attribute Name**|Measurement Method|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Method used to collect groundwater level measurement.|
|**Required/Optional**|Required; if RRP is entered|
|**Unit/Format**|N/A|

### Measurement Accuracy
|**Attribute Name**|Measurement Accuracy|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Accuracy of groundwater level measurement. |
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Collection Agency
|**Attribute Name**|Collection Agency|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Full name of collection or co-op agency that collected groundwater level measurement.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Reporting Agency
|**Attribute Name**|Reporting Agency|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|Full name of reporting agency that reports the groundwater level measurement.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|

### Water Level Comments
|**Attribute Name**|Water Level Comments|
|:----------------------------------------------------|:----------------------------------------------------|
|**Definition**|General description or other notes associated with groundwater level measurement.|
|**Required/Optional**|Optional|
|**Unit/Format**|N/A|
