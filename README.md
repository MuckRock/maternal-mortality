# maternal-mortality
A repository of the Centers for Disease Control and Prevention’s National Center for Health Statistics maternal mortality data, starting from January 2018 and current, as of February 2023; and a selection of state data, from Michigan, Minnesota and North Carolina, about maternal deaths that occurred in 2020, 2021 and provisional data from 2022.

CDC maternal mortality data

The CDC data relies on the 27 underlying cause of death, or ICD-10, codes defined as pregnancy-related. The latest refresh of the CDC encompasses deaths occurring through January 21, 2023, as of February 5, 2023. But there is a lag in reporting deaths, which can take as long as six months depending on the jurisdiction. 

The CDC maternal mortality death codes are the following: 

•	A34 (Obstetrical tetanus)
•	O00 through O99 (Pregnancy, childbirth and the puerperium)

Below is the suggested citation for the CDC data:

Centers for Disease Control and Prevention, National Center for Health Statistics. National Vital Statistics System, Provisional Mortality on CDC WONDER Online Database. Data are from the final Multiple Cause of Death Files, 2018-2021, and from provisional data for years 2022, as compiled from data provided by the 57 vital statistics jurisdictions through the Vital Statistics Cooperative Program.

Michigan, Minnesota and North Carolina maternal mortality data

Why MuckRock analyzed maternal deaths from these three states

MuckRock chose to analyze death certificate data from these states for two reasons:

1.	Michigan, Minnesota and North Carolina provided exhaustive death certificate data encompassing all deaths in a given time period, regardless of whether the death had been reviewed by a medical examiner or coroner or occurred in an inpatient or outpatient setting and;
2.	Data from these states included either pregnancy checkbox information or underlying and multiple, or immediate, cause of death codes, allowing for further analysis on the number of pregnancy-related and pregnancy-associated deaths.

As a result, similar death certificate data from New Mexico, which is exhaustive but does not include pregnancy checkbox information nor underlying and multiple cause of death codes, proved insufficient for our analyses. 

Other datasets from major metro areas, including Chicago’s Cook County and California’s San Francisco, San Diego and Los Angeles counties, only include deaths reviewed or certified by medical examiners or affiliated entities, making a complete analysis of maternal deaths in a given jurisdiction impossible.

Why MuckRock redacted and excluded identifying information from this release

MuckRock chose to remove most personally-identifying information, or PII, from these records in order to protect the privacy of decedents, next of kin, certifiers and funeral homes while still preserving the fields that can shed light on the demographic profiles of those that have died, including race, ethnicity, age, resident county, death year, manner of death and specific causes of death.

Despite these redactions, it is possible to search for public obituaries using the provided data and, in some cases, find the identity of those that have died. This is true with any death certificate data available for public inspection and release and, in its raw form, this data is a public record, according to state statutes.

For more information about MuckRock’s editorial and ethics policies, you can read it here:

If you have questions or concerns about our release of these public records or data or questions about our methodology for excluding most personally-identifying information from these records, you can email us at news@muckrock.com. 

How to analyze state death data with lookup tools

To interpret underlying or multiple cause of death codes found in this data, please refer to the WHO’s ICD-10 lookup tool, found here: 

Limitations and caveats

2022 data for Minnesota and North Carolina is provisional, as of March 2023. It will be updated and made final in mid-2023, and file names will be changed to reflect the shift from provisional to final. As a result, provisional data should not be used to analyze year-over-year trends in these states.

The Minnesota and North Carolina death certificate data includes pregnancy checkbox details while the Michigan data does not. That means the Minnesota and North Carolina data allows us to capture deaths during and shortly after pregnancy that are “pregnancy-associated” and those that are “pregnancy-related.”

The Michigan data does not allow us to look at the broader number of “pregnancy-associated” deaths and, as a result, is limited.

Below are other state-level details, caveats and data dictionary information for Michigan, Minnesota and North Carolina. 

Michigan

The Michigan dataset includes 27 fields, all of which are found in the original file provided by the Michigan Department of Health and Human Services through a data-use agreement. The two provided years are final 2020 and 2021 data.

The Michigan data does not include pregnancy checkbox information but it does included both underlying cause of death and multiple cause of death codes.

Minnesota

Depending on the year, the Minnesota dataset includes either 113 or 114 fields, all of which are found in the original file provided by the state. The 2020 Minnesota dataset does not include a pregnancy checkbox code but does include the pregnancy checkbox text. The 2021 and 2022 Minnesota datasets include both the pregnancy checkbox code and text.

A data dictionary for Minnesota data in its original form is available in this repository — mn_maternal_mortality_data_dictionary.xls — and fields highlighted in yellow have been excluded from this public release in order to preserve identification of the decedent or next of kin.

The data is sorted into final year 2020, final year 2021 and provisional year 2022, with a filter on deaths that have been indicated as recently (within 1 year) or currently pregnant at the time of death. The following counts of pregnancy checkbox deaths in Minnesota, oftentimes referred to by researchers as pregnancy-associated deaths, are as follows:

•	2020: 33
•	2021: 38
•	2022 (as of March 2023, provisional): 18

Within the Minnesota dataset are pregnancy checkbox details — a one-digit code and full text terms used to describe the type of pregnancy at the time of decedent’s death. They are as follows:

•	“2” = “Pregnant at Time of Death”
•	“3” = “Not Pregnant, But Pregnant Within 42 Days of Death”
•	“4” = “Not Pregnant, But Pregnant 43 Days to 1 Year Before Death”

In two cases, specific place of death information in the “place_of_death_type” field was edited to remove the named roadways and were replaced with the term: “roadway.”

In two cases from 2020, “unknown” pregnancy checkbox deaths were included in our analysis because their underlying and immediate cause of death codes were one of the 27 maternal mortality-related codes defined by the CDC. They are indicated as “unknown” in the field “decedent_pregnancy_description.”

North Carolina

The North Carolina dataset includes 52 fields, including 10 fields not found in the original file that have been created by MuckRock for codes related to multiple, or immediate, causes of death. 

The 10 new codes are labeled rac1 through rac10. 

A data dictionary for North Carolina data in its original form is available in this repository — nc_maternal_mortality_data_dictionary.xls — and fields highlighted in yellow have been excluded from this public release in order to preserve identification of the decedent or next of kin.

The data is sorted into final year 2020, final year 2021 and provisional year 2022, with a filter on deaths that have been indicated as recently (within 1 year) or currently pregnant at the time of death. The following counts of pregnancy checkbox deaths in North Carolina, oftentimes referred to by researchers as pregnancy-associated deaths, are as follows:

•	2020: 147
•	2021: 174
•	2022 (as of March 2023, provisional): 122

Within the pregnancy checkbox is the following one-digit code and what it refers to:

•	“2” = “Pregnant at Time of Death”
•	“3” = “Not Pregnant, But Pregnant Within 42 Days of Death”
•	“4” = “Not Pregnant, But Pregnant 43 Days to 1 Year Before Death”
![image](https://user-images.githubusercontent.com/90628055/222923074-a21f7b77-5fe3-4ac6-8548-cc0c68ad69bf.png)
