# Change Log
This change log serves as documentation of the changes made to the data reporting formats. Version numbering follows Major.Minor.Patch versioning schema. The versioning schema is defined as the following:
 - Major = updates with significant enough changes that it is no longer backwards compatible with the previous version.
 - Minor = updates that modify text significantly (for example, a change in a term’s definition) within the data reporting format but not the overall structure of the reporting format.
 - Patch = updates that include very minor changes such as fixing a typo

 The latest release of all materials is v2.1.0. Refer to the sections below for information regarding each release.
## v2.1.0
The v2.1.0 data reporting formats and cross-walk tables incorporated feedback received from the Technical Working Group on v2.0.0. Relatively minor changes were incorporated into version 2.1.0 based on feedback received.

Use the following links to download v2.0.0 word documents:
[Groundwater Elevation Data Reporting Format]()

[Groundwater Elevation Cross-Walk Table]()

[Well Characteristics Data Reporting Format]()

[Well Characteristics Cross-Walk Table]()

Word document versions containing tracked changes between v2.0.0 and v2.1.0 based on the feedback received from the technical working group can be downloaded from the following links:

[Groundwater Elevation Data Reporting Format - with Track Changes]()

[Groundwater Elevation Cross-Walk Table - with Track Changes]()

[Well Characteristics Data Reporting Format - with Track Changes]()

[Well Characteristics Cross-Walk Table - with Track Changes]()

### Changes made to Groundwater Elevation Data Reporting Format:
- The attribute Water Surface Elevation was changed to Groundwater Elevation to differentiate from other data types that utilize the term water surface elevation and to better align with SGMA and CASGEM requirements.
- Changed the Measurement Time attribute to be a required attribute and removed the seconds from the reporting format.

### Changes made to Well Characteristics Data Reporting Format:
- Added new attribute called Survey Type which is intended to capture what type of survey is being conducted for the survey information being reported.
- Changed the Ground Surface Elevation attribute to be required to better align with SGMA and CASGEM requirements.
- Added SGMA and CASGEM as programs that require reporting for the Elevation Survey Date, Elevation Accuracy, Elevation Surveyor Name, Well Completion Report Number, Well Location Description, and Additional Comments attributes.

### Changes made to Groundwater Elevation Cross-Walk Table:
- The attribute Water Surface Elevation was changed to Groundwater Elevation to differentiate from other data types that utilize the term water surface elevation and to better align with SGMA and CASGEM requirements.
- Defined equivalent attribute for the Reporting Agency, Elevation Survey Date, Elevation Accuracy attributes for the SGMA and CASGEM programs.

### Changes made to Well Characteristics Cross-Walk Table:
- Updated list of options for the Coordinate Accuracy attribute under the SGMA program.
- Defined equivalent attribute for the Coordinates Surveyor attribute for the SGMA and CASGEM programs.
- Added definitions for the new attribute called Survey Type for all applicable programs.

## v2.0.0
The v2.0.0 data reporting formats and cross-walk tables incorporated feedback received from the Technical Working Group on v1.0.0. Since the feedback received was based on the initial release, feedback was significant and warranted numerous changes to the data reporting formats and cross-walk tables.

Use the following links to download v2.0.0 word documents:

[Groundwater Elevation Data Reporting Format](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Proposed_GWE_Data_Format_Table_v2.0.0.docx)

[Groundwater Elevation Cross-Walk Table](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/GWE_XWalk_Table_v2.0.0.docx)

[Well Characteristics Data Reporting Format](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Proposed_Well_Characteristics_Data_Format_Table_v2.0.0.docx)

[Well Characteristics Cross-Walk Table](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Well_Characteristics_XWalk_Table_v2.0.0.docx)
 
High-level themes of the changes made in v2.0.0 are summarized for groundwater elevation and well characteristics in the sections below. Word document versions containing tracked changes between v1.0.0 and v2.0.0 based on the feedback received from the technical working group can be downloaded from the following links:

[Groundwater Elevation Data Reporting Format - with Track Changes](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Proposed_GWE_Data_Format_Table_v2.0.0_TrackChanges.docx)

[Groundwater Elevation Cross-Walk Table - with Track Changes](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/GWE_XWalk_Table_v2.0.0_TrackChanges.docx)

[Well Characteristics Data Reporting Format - with Track Changes](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Proposed_Well_Characteristics_Data_Format_Table_v2.0.0_TrackChanges.docx)

[Well Characteristics Cross-Walk Table - with Track Changes](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Well_Characteristics_XWalk_Table_v2.0.0_TrackChanges.docx)

A spreadsheet containing all of the feedback received on v1.0.0 and the associated response to comments are contained in the following spreadsheet:

[Data Reporting Formats v1.0.0 Feedback Tracking Spreadsheet](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Data_Reporting_Formats_Feedback_v1.0.0_Tracking.xlsx)

### Groundwater Elevation Feedback Themes
 - Positive feedback on what attributes are included and required/optional fields
 - Additional clarifications needed on the purpose of the crosswalk and reporting format
 - Highlights the need for unique well identifiers
 - Varying opinions on what elevations should be included each time a measurement is reported
 - Need for standardizing elevation datums
 - Varying opinions on what attributes should or should not be included in the reporting format – elevations and calculated fields

### Well Characteristics Feedback Themes
- Highlighted issues and inconsistencies in current well IDs used across programs​
- Highlights the need for unique well identifiers​
- Any geographic related qualifiers (GW Basin, County, etc.) should be determined on the back-end through GIS
    - Boundaries may change over time requiring updates to these qualifiers​
- Need for standardizing coordinate system and vertical datum​
- Allow users to provide notes when options such as “Other” or “Unknown” are selected (include conditional notes fields)​
- Language modified to improve clarity

## v1.0.0
The v1.0.0 data reporting formats and cross-walk tables were published for feedback from the Technical Working Group on March 27th, 2023. For this reason, the changelog for v1.0.0 is left blank.

Use the following links to download v1.0.0 word documents:

[Groundwater Elevation Data Reporting Format](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Proposed_GWE_Data_Format_Table_v1.0.0.docx)

[Groundwater Elevation Cross-Walk Table](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/GWE_XWalk_Table_v1.0.0.docx)

[Well Characteristics Data Reporting Format](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Proposed_Well_Characteristics_Data_Format_Table_v1.0.0.docx)

[Well Characteristics Cross-Walk Table](https://github.com/CADataReportingFormat/groundwater-elevation-data-reporting-format/raw/main/WordDocs/Well_Characteristics_XWalk_Table_v1.0.0.docx)


