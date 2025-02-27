# CMECS Catalog Changes v.1.1.0 to 1.1.1

## Summary of Changes
Please note that v1.1.1 includes _**changes to unit attributes ONLY**_ and _**DOES NOT**_ include any changes to CMECS units (i.e., concept changes).
Changes were made to select Biotic Component units to correct Unit Codes and spelling in both the cmecs.owl and output table files, and a missing Unit ID for Attached Phoronids.
New and revised Unit Codes were added to the Substrate Component units. 

The _**CMECS Thesaurus**_ (text output of the CMECS Catalog ecological units and implementation guidance) is therefore unchanged from the last release. The most recent version of the _**CMECS Thesaurus**_ is still:
- [CMECS_Thesaurus_v1.1.0.pdf](https://github.com/NOAA-OCM/cmecs/blob/main/CMECS_Catalog_v1.1.0/CMECS_Thesaurus_v1.1.0.pdf)
- [CMECS_Thesaurus_v1.1.0.md](https://github.com/NOAA-OCM/cmecs/blob/main/CMECS_Catalog_v1.1.0/CMECS_Thesaurus_v1.1.0.md)

## CMECS Biotic Component

- _Biotic Group: Attached Tube-Building Fauna_ was erroneously ommitted from the original CMECS Codeset so it was not assigned a Unit Code at that time. Therefore, and the subordinate units under Attached Tube-Building Fauna were erroneously categorized under _Biotic Group: Diverse Colonizers_. New Unit Codes were assigned as follows: to _Biotic Group: Attached Tube-Building Fauna_ (https://w3id.org/CMECS/CMECS_00000067) and its subordinate Biotic Communities.
  - _Biotic Group: Attached Tube-Building Fauna_- unit code change from 2.2.1.3.4 to 2.2.1.24 in the csv and xlsx tables only. There was no unit code in the cmecs.owl file so the correct code has now been added. 
    - _Biotic Community: Attached Phoronids_- new Unit Code is 2.2.1.24.1. Changed in the v1.1.0 cmecs.owl file, added to the csv and xlsx tables
    - _Biotic Community: Attached Pogonophorans_- Unit Code changed from 2.2.1.3.5 to 2.2.1.24.2. Changed in cmecs.owl file and the csv and xlsx tables
    - _Biotic Community: Attached Sabellaria_- Unit Code change from 2.2.1.3.6 to 2.2.1.24.3. Change in cmecs.owl file and the csv and xlsx tables
    - _Biotic Community: Attached Serpula_- Unit Code change from 2.2.1.3.7 to 2.2.1.24.4. Change in cmecs.owl file and the csv and xlsx tables
    - _Biotic Community: Attached Serpulorbis_- Unit Code change from 2.2.1.3.8 to 2.2.1.24.5. Change in cmecs.owl file and the csv and xlsx tables
- Fixed typo in unit name for CMECS_00001653 from Acroprora to Acropora
- Added missing Unit ID for Attached Phoronids (CMECS_00000061) in csv and xlsx tables 

## CMECS Substrate Component (SC) Changes

#### Unit Attribute Changes and Additions
Changes adopted to the Substrate Component in v1.1.0 required the assignment of new Unit Codes in v1.1.1 for most SC units. See [CMECS_1.1.1_UnitCode_Crosswalk.xlxs](https://github.com/NOAA-OCM/cmecs/blob/main/CMECS_Catalog_v1.1.1/CMECS_1.1.1_UnitCode_Crosswalk.xlsx) for a side-by-side comparison of Unit Codes from v.1.0.0 to v1.1.1. Where Unit Codes were revised, the Unit Status _Attribute Change (revised unit code)_ was added.
