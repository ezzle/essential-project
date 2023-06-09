
# [Viewer 6.18.1] Inconsistent rendering of none english chars Issue

https://enterprise-architecture.org/forums/viewtopic.php?f=22&t=2950

# Initial demo repository fron EAS
https://github.com/ezzle/essential-project/blob/main/chars-rendering-test-repository/v6.18_demo_os.zip
# Adapted repository
https://github.com/ezzle/essential-project/blob/main/chars-rendering-test-repository/v6.18_demo_os_test_chars_rendering.zip
## Impacted views list
* View: Application Capability Catalogue by Name
* View: Application Catalogue
* View: Business Capability Catalogue Table
* View: Business Process Catalogue as Table
* View: Business Capability Dashboard
* View: Business Capability Catalogue by Name
* View: Application Dashboard
* View: Application Catalogue (Table)
* View: Application Landscape
* View: Application Rationalisation Analysis
* View: Application Reference Model
* View: Business Process RTO/RPO Mapping
* View: Business Capability Tree
* etc...

## Application Capability
#### Added Instances
A1 TEST chars Account Planning - é&"'§èàçù$@
#### Result
* Instance summary : :white_check_mark:
* Catalog by Name : :x:
## Composite_Application_Provider
#### Added Instances
A1 TEST chars Account Planning - é&"'§èàçù$@ ADEXCell Energy Manager
#### Result
* Catalog :x:
* Summary :x:
## Business Capability
#### Added Instances
A1 TEST chars Account Planning - é&"'§èàçù$@ Acquisition Management
#### Result
* Catalog :x:
* Summary :x:

## Business Process (RTO/RPO Mapping)
#### Added Instances
Process : A1 TEST chars Account Planning - é&"'§èàçù$@ Action Hedging
#### Result
* Catalog :x:
* Summary :white_check_mark:

