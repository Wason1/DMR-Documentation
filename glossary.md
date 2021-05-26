# Glossary
[HOME](index.md)

## Pharmacy

**Medicinal product (MP)**  
MP -> amoxicillin

**Medicinal product unit of use (MPUU)**  
MPUU -> amoxicillin 500mg capsule

**Medicinal product pack (MPP)**  
MPP -> amoxicillin 500mg capsule, 20

**Trade product (TP)**  
TP -> Amoxil

**Trade product unit of use (TPUU)**  
TPUU -> Amoxil 500mg hard capsule

**Trade product pack (TPP)**  
TPP -> Amoxil 500mg hard capsule, 20

**Containered trade product pack (CTPP)**  
CTPP -> Amoxil 500mg hard capsule, 20, blister pack

## Cerner

**Activity data:** Patient-specific information, including orders and results for patient visits. Activity
data is dynamic.

**Activity subtype:** A division of the Order Catalog activity type. Activity subtypes are a
consideration when placing CareNet orders is specific Cerner Millennium solutions such as
Laboratory Management and Radiology Management. For example, anatomic pathology can
have the subtypes AP processing and AP reports.

**Activity type:** A division of a catalog type in the Order Catalog. For example, a catalog type of
Laboratory may have activity types of General Laboratory, Blood Bank, Microbiology, and
Anatomic Pathology. Activity types also may be subdivided into activity subtypes. For example,
Anatomic Pathology may have the activity subtypes of AP Processing and AP Reports. Each
activity type is associated with a specific catalog type. Every item in the Order Catalog must
have a catalog type and an activity type.

**Acute care:** Acute care refers to acute illnesses or needs which can include post-trauma care,
emergency care, intensive care, surgical and post-surgical care, obstetric care, and so forth.
Acute care facility:** A facility which offers care for acute illnesses or needs which can include
post-trauma care, emergency care, intensive care, surgical and post-surgical care, obstetric
care, and so forth. Acute care facilities include hospitals, emergency care facilities, and
ambulatory surgery centers.

**ADT:** Stands for Admitting, Discharge, Transfer (ADT). Also known as a patient registration
system, the ADT system typically captures patient demographic information (religion, race, date
of birth, name, type of visit, and so on) as well as information about the patient's admitting,
attending, and referring physicians. The ADT system also provides a means of bed
management (who is in that bed?).

**Add on the Fly (AOF):** Not only can code sets be populated by Core Code Builder, Content
Manager, and/or solution specific tools, they can also be populated by an optional feature called
Add on the Fly. This is a function that is engaged for the entire domain, if chosen by the client
to use. With this feature, when Millennium receives an alias that is not built in the system, AOF
gives the interface permission to add this new code value, alias it and use it for future
transactions. This feature requires that an analyst modify the display value of the newly built
code value as the system creation does not know what the client would want this value
displayed as for end-users. The system creates this code value and provides a display of the
alias—the only value known at that point. This is a process that needs to be determined if
applicable by each individual client.

**Admission:** The official acceptance of inpatients into a hospital or other inpatient health facility.
Inpatients typically stay at least overnight and are provided with room, board, and nursing
service.

**Admitting department:** The hospital department which collects and records patient
demographic and financial information on inpatients for registration purposes; coordinates
patient room assignments; schedules preadmission testing; records all patient movement
including transfers and discharges for the purpose of maintaining accurate census data; and
disseminates patient information to other hospital departments.

**Alias:** A number or identifier used to represent or describe an entity, such as a person or an
organization. Different systems may use different values to represent the same piece of
information. For example, one system may use PG7 to indicate someone speaks Portuguese,
while another system may use PT to indicate someone speaks Portuguse. These different
values are recorded in the Cerner Millennium database as aliases for the corresponding
standard value for language within Cerner Millennium. In this way, aliases allow the Cerner
Millennium system to translate information coming from other systems. When used in this
context, aliases are often referred to as code value aliases. Aliases are also important in
identifying people, personnel, organizations, encounters, and orders. For example, a medical
record number is often used as an alias for a person. A person's medical record number is used
to identify that person within the system.

**Alias pool:** A group of aliases that is associated with the same organization. There are five
types of alias pools in Cerner Millennium:** Person, personnel, organization, order, and
encounter. A person alias pool, for example, is used to define a set of person identifiers (such
as medical record number) used by an organization. The same alias pool can be used by more
than one organization. For example, two hospitals can share the same medical record number
alias pool.

**Alias pool type:** Five core types of alias pools exist; person, encounter, personnel, order and
organization. There are additional alias pool types that are product specific.

**Ambulatory care:**Medical or health services provided on an outpatient basis. It usually implies
the patients are not staying in the hospital and came to the facility for a specific outpatient
treatment or service.

**Ancillary services:** Therapeutic or diagnostic services provided by specific hospital
departments (other than nursing service) such as x-ray, laboratories, anesthesiology, respiratory
therapy, electroencephalography, heart station, rehabilitative medicine, and pharmacy.

**Ancillary synonym:** Alternate name for an Orderable seen only by a specific departmental
Cerner Millennium module such as Laboratory Management or Radiology Management.

**Application Group:** Site-defined groupings of applications and tasks. Users are assigned
access to one or more application groups by position.
Application Groups are composed of applications and tasks which are granted to positions to
drive access those positions have within Millennium.

**Authenticated feed:** A feed provided by a system owning the patient demographic information.
Typically, an ADT (Admit, Discharge, and Transfer) System.

**Authentication:** The security process that identifies users with usernames and passwords.
Authentication controls who can access the Cerner Millennium system.

**Authorization:** The security process that identifies what a particular user can do once they
have accessed the system. For example, authorization determines whether a user can access
data stored for a particular patient.
**Bed:** A bed located in a hospital or nursing home used for inpatient use. Number of beds is
used as one critical measure of an institution's capacity and size.

**Building:** A way to differentiate between locations with the same name. A building must be
included in the patient care hierarchy.

**Care plan:** An outlined plan of care for a patient related to a diagnosis (such as Multiple
Sclerosis, Alzheimer's disease, or a fractured femur), an event (such as surgery or an upper GI
series), or an education need (such as decubitus care). Care plans are more robust than care
sets because their components include comments and orderable items and can be viewed over
time.

**Care set:** A set of commonly requested orders entered through a single mnemonic in which
individual orders can be included, excluded, or designated as required. For example, a
physician may establish a care set of orders to follow a certain procedure such as cardiac
catheterization.

**Catalog type:** A major division of the Order Catalog. A catalog type can be Pharmacy or
Laboratory, but catalog type is not synonymous with department. For example, Therapy or
Patient Care can be valid catalog types. Each catalog type is associated with a set of activity
types. Every item in the Order Catalog must have a catalog type and an activity type.

**Cerner Classic:** Prior version of Cerner applications, also called Health Net Architecture
(HNA).

**Cerner Command Language (CCL):** A fourth-generation query language patterned after
Structured Query Language (SQL). A significant difference between the two is the fact that CCL
requires a Go statement at the end of each command, while SQL does not.

**Cerner encounter number:** An internal number assigned to an encounter by the Cerner
Millennium® system. It is used to identify the encounter uniquely.

**Cerner Millennium:** The client/server generation used by the Cerner Millennium products.

**Charge point:** A charge point determines the point at which charges are actually generated. An
order event or result event are examples of common charge points.

**Chart:** In Charting, a chart is a report of clinical information about a patient or specimen
created by Charting.
²In PowerChart, a chart is the aggregation of all information recorded about a person's health
status. All inpatient and outpatient visits, lab results, procedures, evaluations, orders, reports, xrays,
photographs, films, audio recordings, and other multimedia information pertaining to a
person's health are considered part of the total chart. Historically, the chart has been paperCerner based. Recently, many institutions have begun storing patient information in databases
accessible by computers, and the chart has become increasingly electronic.

**Chart access security (Relationship):** Permits tracking of clinical affiliation of user to specific
patient. Relationships may be associated to self-declared positions or automatically with a
patient during patient registration, such as attending MD.

**Citrix:** A terminal server system used to access Windows-based applications from remote
locations.

**Cerner Knowledge Index (CKI):** A broad electronic collection of clinical reference data
compiled and maintained by Cerner and its clients for use with specific Cerner applications
(such as PowerNote). Reference data elements in the CKI span a number of domains, including
order catalog entries, PowerNote Care Designs, event codes, and so on. To manage updates to
the reference data, each element within a domain is uniquely identified by a combination of CKI
Source and CKI Identifier. Maintaining this type of clinical reference data in a structured,
codified format, ensures consistency, prevents redundancy, and enables data analysis.

**Client:** Client is an organization type used to represent a specific patient population.

**Client tier:** A process that runs on a personal computer or workstation and relies on a server to
perform some operations. For example, an email client is an application that enables you to
send and receive email.

**Code set:** Grouping of like data elements that consist of display values, code values, and code
value aliases.

**Code value:** A unique system-generated number assigned to a common display value when
standard code sets are configured. For example, the standard display value Portuguese in the
language code set might be assigned the Code Value 2553237765, while Sign Language could
be assigned 2553237817.

**Code value alias:** See alias.

**Column:** Alternate name for database field.

**Common Data Model (CDM):** The Common Data Model (CDM) defines the relationship of
data in the Cerner Millennium system.

**Community hospital:** A hospital that is established to meet the medical and health needs of a
specific geographic area. Usually these hospitals are non-profit but can be proprietary for profit.
Community hospitals are general non-federal, short-term, and general care hospitals.

**Community Medical Record Number (CMRN):** A common identifier that more than one
institution or contributor system can use to recognize a patient. Whereas each institution may
have its own unique MRN format, all share one common community MRN format

**Component:** Separate parts of a field in an HL7 message. Some common examples include
the following items:** Address1, address2, city, state, zip code.

**Component separator:** Special character, ^ used to separate HL7 fields into separate
components.

**Context-sensitive help:** Also referred to as What's This? Help, context-sensitive Help is a
Cerner Millennium Help feature that displays an explanation of an element that is displayed.
You can access this type of Help in several ways:
 Click Info on the toolbar, and then click the element for which you want information.
 Click a menu command and then press F1. Click the Question Mark button on the
title bar of a dialog box and then click the element for which you want information.
To close the Help window displaying the information, click Close.

**Contributor source:** A set of aliases used by one or more contributor systems. Standard code
sets include information on how to translate the aliases included in the contributor source into
the standard values used in Cerner Millennium. A contributor source is the set of reference data
the foreign system sends. The contributor source is made up of all the potential code value
aliases that a particular interface might send.

**Contributor system:** A non-Cerner Millennium system that is sending information to Cerner
Millennium through an interface. Also referred to as a data feed or legacy system. Contributor
systems are the equivalent of the foreign or external systems that send data into the Cerner
Millennium database

**Core:** The common components shared by all Cerner Millennium applications. For example,
standard code sets provide common display values for all Cerner Millennium applications and
are therefore part of Core.

**CPT code:** A current procedural terminology (CPT) code refers to a medical standard. The
American Medical Association (AMA) updates CPT codes annually.
Physicians' Current Procedural Terminology is a list of descriptive terms and identifying CPT
codes for reporting medical services and procedures performed by physicians. The purpose of
the terminology is to provide a uniform language that accurately describes medical, surgical,
and diagnostic services, and thereby provides an effective means for reliable nationwide
communication among physicians, patients, and third parties.
A CPT-4 code identifies the fourth edition of Physicians' Current Procedural Terminology.

**Critical result:** A value for a given result that is higher or lower than the range recognized as
normal by the site. Critical results are displayed in a special font color, usually red. Critical
thresholds are defined by the site for each element on the Flowsheet.

**Database tier:** A collection of information organized in such a way that a computer program
can quickly select specific pieces of data. You can think of a database as an electronic filing
system. In Cerner Millennium, the database is managed by an Oracle relational database
management system (RDBMS).

**The database stores three types of data:** Reference data, Activity data, and Information about
the database itself.

**Data value:** The intersection of a database row and a database column when an actual value is
stored. For example, the name_last_key of person_id is SMITH.

**Data element:** A data element is a piece of demographic information supporting patient
registration or patient order information (for example, the patient's name).

**DCP synonym:** Direct Care Provider (DCP) synonym is an alternate name for an orderable
item seen only in PowerChart ( PowerChart.exe) and PowerChart Office (PCOffice.exe).

**Discern Explorer:** See Cerner Command Language (CCL).

**Display:** Textual name of individual data values shown to users throughout Cerner
Millennium applications.

**Domain:** A named environment inherent in Cerner's distributed system architecture. Server
resources in a domain are secured by a proprietary implementation of the Kerberos
authentication protocol. Domains naturally span all nodes participating in the distributed system.

**Dynamic data:** See Activity Data.

**Electronic medical record (EMR):** An electronic medical record (EMR) is a computer-based
patient medical record. An EMR facilitates access of patient data by clinical staff at any given
location, accurate and complete claims processing by insurance companies, building automated
checks for drug and allergy interactions, clinical notes, prescriptions, and scheduling.

**Electronic signature:** The act of verifying or accepting a transcribed report online instead of
signing the physical piece of paper on which the report is printed

**Emergency Department (ED):** The department or unit of a hospital which provides the medical
services necessary to sustain life or to prevent critical consequences. This area sometimes
provides non-urgent, walk-in care and is usually staffed 24 hours a day by physicians and
nurses.

**Encounter:** A single patient interaction. The following interactions are examples of encounters:
Patient - registered as an inpatient
Patient - registered as an outpatient

**Event code:** A name against which discrete pieces of clinical data are stored. Event codes are
required for the storage of clinical results. Examples include Sodium, Carbon Dioxide, Chloride,
and Potassium. Event codes are associated with primitive event sets to allow the display of
clinical information in PowerChart.

**Event set:** Groupings of primitive event sets and/or other event sets used to organize the
display of clinical data in PowerChart and Charting. In PowerChart, event sets are nested to
show like information together.

**Event set hierarchy:**Encompasses all event sets, including primitive event sets and event
sets to logically group results. Consists of the Cerner required event sets that are part of core
and any number of client-defined event sets.

**Facility:** An organization that provides patient care. An organization must be designated as a
facility in order to build locations for the organization. A facility is always at the top of the patient
care hierarchy.

**Field:** Space in a database allocated for a particular item of information. Most fields have
certain attributes associated with them. For example, some fields are numeric whereas others
are textual, some are long, and others are short. In addition, every field has a name called the
field name.

**Field separator:** Special character | used to separate HL7 message segments into individual
fields.

**Financial class:** Type of payment used by patient. Possible financial classes included worker's
compensation, commercial insurance, private pay, Medicaid, and Medicare.

**Financial number:** A unique number assigned to the patient for use by your financial
department's billing system. A new financial number (FIN) typically is assigned to each
encounter.

**Flowsheet:** A spreadsheet of a selected patient's clinical results for a certain time span. All
types of results are arranged on a grid that is sorted by result categories on one axis and by
time increments or specific times on the other axis.
Any result can be opened to view its creation history, status, and, when applicable, its
comparison to normal values for its result type. New results can be entered into the Flowsheet
by electronic capture (handheld devices at the bedside, for example), by direct charting, or by
feeds from other systems. The data is refreshed automatically at user-defined intervals or can
be refreshed manually at any time.

**Foreign key:** A key field that identifies records in a different table. A foreign key is a Primary
key in a different table.

**Frequency:** A schedule of events. For example, the schedule for administration of medication
orders are usually described using standard frequency codes for specific times of day (BID),
intervals of time (q8h), or unscheduled times (PRN).

**FSI:** Foreign Systems Inbound. Refers to those interfaces coming into the Cerner
Millennium database from a foreign system.

**Graphical user interface (GUI):** A program interface that takes advantage of the computer's
graphics capabilities to make the program easier to use. Microsoft Windows is a GUI.

**HL7®:** An acronym for Health Level Seven, which is a healthcare industry standard protocol for
electronic data exchange.

**HL7 message:** See message.

**HL7 segment:** See segment.

**Home health care:** A formal program which offers patients medical and nursing care,
therapeutic services, and social services in their homes.

**
HNA:**Health Network Architecture.
Inbound transactions:** Transactions received by the communications client from foreign
systems.

**Inpatient:** A patient who has been admitted to the hospital or other health care facility for at
least one night for the purpose of receiving diagnostic treatment or other medical service.

**IP address:** An address in the form of a name or number that identifies a location on the
TCP/IP network.

**Laboratory department:** The unit or department in a hospital or health care facility which is
designed to perform clinical tests and procedures through detailed analysis and examination of
specimens. The laboratory is typically divided into sections, including Anatomical Pathology,
Clinical Chemistry, Cytopathology, Hematology, and Microbiology.

**Legacy system:** Another term for contributor system.

**Legal description:** Description of an orderable item. Seen on all reports and requisitions in
Cerner Millennium.

**Location:** A physical place that is used for patient care. Locations are built according to the
patient care hierarchy. Examples include a nursing unit, room, or bed.

**Medical record:** A patient file containing information which clearly identifies the patient, justifies
the patient's diagnosis and treatment, and accurately documents the results. The record serves
as a basis for planning and continuity of patient care and provides a means of communication
among the physicians and other health professionals involved in the patient's care. The record
also serves as a basis for review, study, and evaluation on serving and protecting the legal
interests of the patient, hospital, and responsible practitioner. The content of each record is
usually confidential and is the property of the hospital.

**Medical record number (MRN):** A permanent number used to identify the patient. It typically
remains unchanged even if the patient has multiple encounters. Otherwise known as MRN.

**Message:** A block of data delivered between a client and a server. It is the primary means of
information exchange on the message bus.

**Message bus:** A piece of software responsible for the accurate and efficient delivery of data
between applications on a network. Servers use the message bus as a primary means of
registering services that client applications ultimately seek out and use.

**Trigger Event:** An HL7-standard identifying the event that triggered the transaction (such as
A01, A02, or A03). It further defines the message type.

**Message type:**Each HL7 message type is represented by a three-character code that
accompanies the message and that identifies the message type based on HL7, such as ADT or
ORM. Used for message routing and object library designation.

**Middleware:** Client and server software components that provide communication between the
client and server.
9
Non-acute care facility:** A facility that offers care for non-acute needs or illnesses may include
chronic illnesses. Non-acute care facilities include doctor's offices, healthcare clinics, nursing
homes, and rehabilitation centers.

**Nursing unit:** The geographical area of the hospital in which the nursing organization
functions. In this area, patient care takes place on a long or short-term basis. Many hospitals'
nursing units are organized by type of care including medical-surgical, intensive care, cardiac
care, pediatrics, labor/delivery/recovery and postpartum, orthopedics, and so on.

**OCF:**Open Clinical Foundation. Used for displaying results.

**Order:** Something a healthcare provider determines is necessary to diagnose or treat a patient.

**Orderable item:** Something that can be ordered. In Cerner applications, an orderable item can
be selected and used to create an order. Different types of orderable items can be present in
the list, depending on the applications installed and user security. Some examples include
medications, laboratory tests, and radiology procedures.

**Order catalog:** Compilation of all orderable items and most billable items that are shared
across all Cerner Millennium applications.

**Order category display:**Orders are grouped and displayed in a hierarchy according to clinical
interest. The site determines the hierarchy and the orders contained in it.

**Order entry format:** All details which are gathered in order to complete a procedure, test, or
service. This format is not unique to an orderable item; it is unique to a catalog type.

**Organization:** An organization is any business entity relevant to the healthcare process.
Organizations are part of Core Typical organizations include hospitals, insurance companies,
employers, physicians' offices, and clients.

**Organization type:** A descriptor assigned to an organization in order to designate patient care
locations, provide specific product functionality and as a filter mechanism. Examples include:
employers, insurance companies, blood bank manufacturer, physician office and others.

**Outbound transactions:** Transactions to be sent by the Open Engine (OE) communications
client to foreign systems.

**Outpatient:** A patient receiving ambulatory care at a health facility, such as a hospital, without
being admitted as an inpatient.

**Password:** A security token used to authenticate a user's identity. Passwords can contain up to
256 alphanumeric characters.

**Patient care hierarchy:** The hierarchy that describes the physical locations that can be
occupied by patients. The hierarchy includes facility, building, nursing unit or ambulatory
location, room, and bed.

**Patient identification:** The process of determining whether two or more people about whom
the system has information are actually the same person. If the determination is made that the
people are the same, then the information is stored under one-person record. This prevents the
120
addition of duplicate sets of information in the database while preserving the integrity of patient
records. There are two steps in person identification:** Person match and person reconciliation.

**Person Combine:** The process of combining two medical records that exist for the same
person or encounter. Person reconciliation can combine two authenticated records or an
authenticated and unauthenticated record automatically. If person 1 and person 2 are
determined to be the same person, P2 is combined into P1 and P2 will have an active indicator
of 0. See Person Reconciliation in the glossary

**Person data model:** Person data is stored in a section of the Common Data Model (CDM)
called the person data model. In the person data model, patient information is stored on the
person table.

**Patient demographics:** Information defined for the person or encounter. Demographic
information includes elements such as the current location (like a nursing station, room, and
bed), alias identification values, age, birth date, gender, and maiden name.

**Person/encounter security:** Three different solutions to maintain person and encounter
security include:**location security, encounter organization security and confidentiality levels.

**Person match:** The process of searching existing person records to see whether we already
have a record for the person about whom we have received new information. For example, if a
contributor system sends a new lab result, the Cerner Millennium system must determine
whether this result is for a person who already exists in the database or whether there needs to
be a new person record created because this is the first information Cerner Millennium has
received about the person. This process is sometimes referred to as match and tag. This is a
mandatory process within Cerner Millennium.

**Person reconciliation:** Automated combines. In person reconciliation, the system determines
whether two more existing person records should be combined because they represent
information about the same person. This is an optional process and is only applicable to
authenticated feeds in Cerner Millennium.

**Primary identifier:** Aliases used for person identification and from which alias pools originate.
Criteria for Person Match.

**Primary key:** A unique value required for each record within a database table. Primary keys
are system assigned, unique, and non-repeating.

**Primary synonym:** Name for an orderable item that all departments will see and must
recognize. Often the same as Orderable Description.

**Primitive event sets:** The lowest viewable values in PowerChart and Charting. At least one
event code must be associated with a primitive event set to be displayed in PowerChart and
Charting.

**Process:** Programs running on the back end are referred to as processes.

**Psychiatric hospital:** A specialty institution which provides inpatient and outpatient care and
treatment for the mentally ill.

**
Radiology:** A branch of medicine which deals with the use of x-rays and other forms of radiant
energy in the diagnosis and treatment of disease.

**Radiology department:** That unit in a hospital specifically designed to use x-rays and other
radioactive elements for the diagnosis and treatment of patients. This department is directly
supervised by a radiologist (physician). This department could also include radiation therapy or
nuclear medicine sections.

**Reference data:** Static information. This information is configured one time and used over and
over.

**Reference database:** A database provided with Cerner applications for review and use in the
applications. The content is updated on a regular basis by a third-party vendor and cannot be
modified directly by the user.

**Result:** The answer to a detail procedure.

**Result type:** The type of result assigned to a specific procedure, such as numeric, alphabetic,
or calculation.

**Review (orders):** The process of checking an order for accuracy and appropriateness. Orders
subject to nurse review are designated with an icon that resembles a pair of spectacles. The site
defines which orders require nurse review.

**Review (results):** To verify a result. Results entered in the Flowsheet become part of the
patient record. Whether the result records a discrete task assay, document, or laboratory value,
the person ultimately responsible for its accuracy must verify or review the result and sign it.
When signed by the appropriate person, the result has the status of Authenticated (final).

**Row:** A single record in a database table.

**Secondary identifier:** Identifier that is used to confirm identity after a Person Match. Can
include Social Security Number (SSN), first name, last name, date of birth (DOB), and sex.

**Security:** Strategies designed to ensure timely and responsible access to patient and other
data that can comprise an Electronic Medical Record (EMR).

**Segment:** A logical grouping of information within an HL7 message. Segments are identified by
three-character codes, such as MSH, PID, and OBR.

**Server:** A software run-time unit that registers a service with the message bus and
subsequently handles clients or requests intended for that service. A server in this context is a
process that provides services to requesting applications. Often referred to as an application
server.

**Service:** A name registered with the message bus that uniquely identifies a unit capable of
processing requests. Typically, one service can process one or more requests. A service should
not be confused with a server. Services are abstract in the sense that they specify a logical unit
of work regardless of where the work is performed. Servers are the physical entities that
implement the logical unit of work associated with a service.
122

**Service resource:** A person, place, or thing that can be scheduled to provide a service.
Examples include a radiology exam room or an instrument. Service resources are not generally
part of Core.

**Service resource hierarchy:** Relevant to specific Cerner Millennium products and not part of
core. Scheduled to provide a service as part of the healthcare process.

**Standard code sets:** Provide common display values in all Cerner Millennium applications as
well as the information necessary to translate incoming information from non-Cerner
Millennium systems into these common values. Standard code sets deal with descriptive
information about people, orders, and results. For the person, this includes demographic
information, such as race, religion, and gender. Standard code sets have two parts:** Standard
values and aliases.

**Table:** Refers to data arranged in rows and columns. In relational database management
systems, all information is stored in the form of tables.

**Unauthenticated feed:** An interface from a system that does not own the patient demographic
data it is sending. Usually a clinical system; this system is a valid source for clinical information.

**Universal interface specification document:** Contains a breakdown of all the fields listed in a
particular HL7 segment.