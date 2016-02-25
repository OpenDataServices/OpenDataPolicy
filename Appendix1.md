# Appendix 1: Open data workflows

These workflows and checklists are used by \[organisation\] to prepare, publish and update our open data. These are linked to and detailed in our open data policy. A data release document is provided with published open data after completing this workflow.

### Contents

[Data privacy (principle 1)](#data-privacy-principle-1)

[Data quality criteria (principle 2)](#data-quality-criteria-principle-2)

[Data segmentation (principle 4)](#data-segmentation-principle-4)

[Data codes checklist (principle 5)](#data-codes-checklist-principle-5)

[Data formats checklist (principle 6)](#data-formats-checklist-principle-6)

[Open data licence (principle 7)](#open-data-licence-principle-7)

[Data release checklist (principle 8)](#data-release-checklist-principle-8)

[Open data publishing channels (principle 9)](#open-data-publishing-channels-principle-9)

[Data publication schedule (principle 10)](#data-publication-schedule-principle-10)

[Open data feedback mechanisms (principle 11)](#open-data-feedback-mechanisms-principle-11)

[Attribution checklist (principle 13)](#attribution-checklist-principle-13)

[Data take down (principle 14)](#data-take-down-principle-14)

Data privacy (principle 1)
==========================

When preparing information for publication, we will ensure the data is free from information that can be used on it’s own or with other information to identify a living person, by checking:

| **Consideration**                                                                                                                        | **Action**                                      |
|------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------|
| Does the data contain [personal or sensitive personal information](#personal-and-sensitive-personal-information) about individuals?      | If yes, then remove the information             |
| Does the data contain any [identifiers](#identifiers) that can be used to find personal information in external systems?                 | If yes, then remove the information             |
| Are counts small enough (&lt; 5) to allow an individual to be identified?                                                                | If yes, then refer to identifiers section below |

Personal and sensitive personal information
-------------------------------------------

[Personal information](https://ico.org.uk/for-organisations/guide-to-data-protection/key-definitions/) is any information about a living person that can be used to identify them or to compromise their privacy.

When \[organisation\] checks for personal information, we include:

-   name

-   birthday

-   full address

-   telephone number

-   email address

-   age

-   gender

-   occupation

-   bank details

-   document numbers such as passport, national insurance and NHS numbers

Sensitive personal information is explicitly defined in the Data Protection Act as:

-   Racial or ethnic origin

-   Political opinions

-   Religious beliefs or other beliefs of a similar nature

-   Trade Union membership

-   Physical or mental health or condition

-   Sexual life

-   Alleged or actual criminal offences

-   Legal proceedings or judgements

We may publish or use overall counts, for example of gender, age, and occupation. When we do, we will check that counts are not [small enough](http://www.hscic.gov.uk/media/13158/Small-Numbers-Procedure/pdf/Small_Numbers_Procedure.pdf)[ to identify a person](http://www.hscic.gov.uk/media/13158/Small-Numbers-Procedure/pdf/Small_Numbers_Procedure.pdf).

Identifiers
-----------

An identifier is any information that allows an individual to be picked out of a group. This could be a [*direct identifier*](http://ptac.ed.gov/glossary/direct-identifier), for example document numbers or contact information. These are also personal information and are covered in the personal and sensitive personal information section.

When \[organisation\] checks for identifiers, we will include document numbers, such as:

-   passport number

-   national insurance number

-   NHS number

We will also include other numbers where they relate to a specific person, such as:

-   personal telephone number

-   personal e-mail address

-   personal social media profiles e.g. Twitter, Facebook or LinkedIn

Identifiers can also in [indirect identifiers](http://ptac.ed.gov/glossary/indirect-identifier), where the information can combined with other information to identify an individual. These can include:

-   birthdays, joining dates, admission and other dates

-   places, for example post codes, co-ordinates, place of birth

-   a person’s age

-   unusual details which aren’t common like:

    -   education and graduation details (1st from Oxford in Biolinguistics 1999)

    -   occupation and location (Bus driver in the Shetland islands)

When \[organisation\] checks for indirect identifiers, we will check individual records and groups with low counts. To reduce the risk of revealing personal information, we will:

-   Group information: for example, by day instead of individual records

-   Redact information: by removing or blanking out the data

Reduce precision: for example, by rounding numbers up or down

Data quality criteria (principle 2)
===================================

When preparing data for publication, we will check:

| **Consideration**                                                                   | **Action**                                                    |
|-------------------------------------------------------------------------------------|---------------------------------------------------------------|
| Do results for grouped information have values outside what’s normal for the group? | If yes, then check source data or reports to validate figures |
| Are there blanks, zero or unusual dates that could be defaults (eg: 1/1/1900)?      | If numerous, then check source data. <br>If acceptable, then record this in the data release           |                         
| Are date and number formats consistent across the dataset?                          | if not, then reformat to the agreed standard                  |
| Are there duplicates for values that should be unique?                              | if yes, then check source data or reports to validate values  |

Data segmentation (principle 4)
===============================

When preparing data for publication, we will check:

| **Consideration**              | **Action**                                                                      |
|--------------------------------|---------------------------------------------------------------------------------|
| The overall physical file size | If over \[maximum size\], then check contents and consider further segmentation |

Data codes checklist (principle 5)
==================================

When preparing data for publication, we will:

<table>
<tr><th><b>Consideration</b></th><th><b>Action</b></th></tr>
<tr><td>Provide codes and names for geographic areas</td><td>Describe this in the data release document for:<br><ul><li>Local authorities</li><li>Wards</li><li>Clinical Commissioning Groups</li></td></tr>
<tr><td>Provide and/or signpost data users to the latest lookup of any codes used.</td><td>Describe authoritative sources such as Ordnance Survey, Office for National Statistics and the NHS in the data release document</td></tr>
<tr><td>Ensure that a lookup and/or explanation is provided when using internal / [organisation] specific codes</td><td>Describe this in the data release document</td></tr>                                                                                      
</table>

Data formats checklist (principle 6)
====================================

When preparing data for publication, we will:

| **Consideration**                                                                                | **Action**                         |
|--------------------------------------------------------------------------------------------------|------------------------------------|
| Release spreadsheets and tables in standard open formats                                         | Release as: <br> Open Document Format for spreadsheets (.odf) <br>Comma Separated Format for flat files (.csv) |
| Ensure that the format is open and accessible when working with other data standards and systems | Consider XML, JSON or RDF formats as open. Check with standard or publication organisation. |
| Avoid publishing data in closed, proprietary and formats that make the data inaccessible.        |                                    |

Open data licence (principle 7)
===============================

When publishing data, we will always ensure a relevant licence is provided.

Our default licence is a \[licence-type\]

| **Consideration**                                                         | **Action**                                                                        |
|---------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| Does the dataset fit within the default licence for \[organisation\]? <br>See: \[licence-type\]  | If yes, then describe this is in the data release document <br>If no, then select alternative, and describe this is in the data release document  |
| Does the data contain any information that is derived from other sources? | If yes, then give details of the sources is in the data release document <br>If there may be an issue with these derivations, then seek advice                  |

Data release checklist (principle 8)
====================================

When publishing data, we will always ensure documentation is provided by checking:

| **Consideration**                                                                            | **Action**                                                                                                    |
----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Is there a guide to using the data?                                                          | If no, provide details about the license, scope, purpose, relevant dates and production method of the dataset |
| The column headers and data labels are easy to understand.                                   | If not, provide explanations in the data release document                                                     |
| Column headers are used once and not repeated                                                | if not, rename the affected columns                                                                           |
| For aggregated datasets, check that aggregations are explained and logged.                   | Ensure these are described in data release document                                                           |
| That time formats and periods are common standards (eg: financial quarters, calendar months) | If there is a bespoke date format or period, then describe this in data release document                      |


Open data publishing channels (principle 9)
===========================================

When publishing data openly, we will check:

| **Consideration**                                                                                                             | **Action**                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| File names are logical, descriptive and consistent, for example: <br>volunteers\_statistics.csv rather than volunteersstats(1)-EDITED.csv | Use the shared naming convention wherever possible: 'location-dataset-format-main.csv' example: <br>'oxfordshire-groups-openvcs-main.csv' |
| When hosting data files, always ensure that the file is accessible, and free from any security barriers, passwords or blocks. | If there is an issue with the link to the data file, get advice.                                                                      |

Data publication schedule (principle 10)
========================================

When publishing - and updating - data, we will do this as quickly as possible by checking:

<table>
<tr><th><b>Consideration</b></th><th><b>Action</b></th></tr>
<tr><td>Datasets are updated in an acceptable timeframe. For example:<br><ul><li>Monthly updates - two weeks after period ends</li><li>Quarterly updates - one month after period ends</li><li>Annual updates - three months after period ends</li></td><td>If data publication was delayed, describe why in the data release document</td></tr><tr><td>Ensure that relevant older data can be accessed after an update - that it is not deleted or destroyed.</td><td>Make sure the new data is available along with older data - Where data must be overwritten, document reasons in data release document</td></tr></table>                                                              

Open data feedback mechanisms (principle 11)
============================================

When seeking, collecting and receiving feedback on our data, we will:

| **Consideration**                                                                | **Action**                                                      |
|----------------------------------------------------------------------------------|-----------------------------------------------------------------|
| Reply to let you know we’ve received your feedback when you send it to us online | We will let you know if we can take an action and when          |
| Reply to feedback from face-to-face meetings or workshops                        | Where appropriate: <br>1.  Create a new issue for the related dataset(s)<br>2.  Note the source of the observation / remark<br>3.  Acknowledge we have received and / are working on the issue  |

Attribution checklist (principle 13)
====================================

When using datasets published by other organisations, we will describe the source and provide attribution in our data release document, making sure we include:

| **Attribution**                                   | **Comment**                                         |
|---------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Name of the dataset utilised                      | eg: Adult Learning Centres                                                                                                                                                                                                                                                                                                                    |
| Publisher of dataset                              | eg: Manchester City Council                                                                                                                                                                                                                                                                                                                   |
| Source URL (from where the data can be retrieved) | eg:[http://www.manchester.gov.uk](http://www.manchester.gov.uk/site/custom_scripts/getmetadata.php?guid=a65c8dfb-7371-4db9-a3b3-a9e4be72a493) |
| Date retrieved                                    | in DD/MM/YYYY format                                                                                                                                                                                                                                                                                                                          |
| Notes on usage                                    | Any changes we’ve made to the original dataset                                                                                                                                                                                                                                                                                                |

Data take down (principle 14)
=============================

After publishing open data, we will remove or republish the dataset if:

| **Consideration**                                                                                                                                                                    | **Action**                                                                        |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| We discover internally that published open data contains [*personal or sensitive personal information*](#personal-and-sensitive-personal-information)[7] about individuals           | 1.  Review the dataset against the data privacy checklist <br>2.  Remove or re-publish the dataset if possible and appropriate                   |
| We are notified that published open data we own or collected contains [*personal or sensitive personal information*](#personal-and-sensitive-personal-information) about individuals | 1.  Review the dataset against the data privacy checklist<br>2.  Remove or re-publish the dataset if possible and appropriate<br>3.  Let the notifier know the outcome |
| We are notified that published open data from a third party contains [*personal or sensitive personal information*](#personal-and-sensitive-personal-information) about individuals  | 1.  Review the dataset against the data privacy checklist<br>2.  Contact the owner and provide details of the issue<br>3.  Remove or Re-publish the dataset if possible and appropriate<br>4.  Let the notifier know the outcome               |
| We are asked to take down published open data we own or collected for another reason                                                                                                 | 1.  Review the complaint and ask for advice where it’s needed<br>2.  Take down the dataset if appropriate<br>3.  Let the notifier know the outcome                                              |
| We are asked to take down published open data we don’t own for another reason                                                                                                        | 1.  Review the complaint and ask for advice where it’s needed<br>2.  Take down the dataset if appropriate (or the notifier is the confirmed owner)<br>3.  Let the notifier know the outcome                                              |
