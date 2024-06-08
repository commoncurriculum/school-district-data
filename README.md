# School District Data from NCES

Public school data is exported from urban.org
Private school data is downloaded from [nces](https://nces.ed.gov/surveys/pss/pssdata.asp)

## Schema for US Private and Public Schools

| name                                                | field_type         |
| --------------------------------------------------- | ------------------ |
| dataCurrentAsOf                                     | String             |
| demographicsAmericanIndianAlaskaNativeCount         | Null               |
| demographicsAmericanIndianAlaskaNativePercentage    | Null               |
| demographicsAsianCount                              | Null               |
| demographicsAsianPercentage                         | Null               |
| demographicsBlackCount                              | Null               |
| demographicsBlackPercentage                         | Null               |
| demographicsHispanicLatinoCount                     | Null               |
| demographicsHispanicLatinoPercentage                | Null               |
| demographicsNativeHawaiianPacificIslanderCount      | Null               |
| demographicsNativeHawaiianPacificIslanderPercentage | Null               |
| demographicsTwoOrMoreRacesCount                     | Null               |
| demographicsTwoOrMoreRacesPercentage                | Null               |
| demographicsWhiteCount                              | Null               |
| demographicsWhitePercentage                         | Null               |
| enrollmentGrade1                                    | Int32 OR Null      |
| enrollmentGrade10                                   | Int32 OR Null      |
| enrollmentGrade11                                   | Int32 OR Null      |
| enrollmentGrade12                                   | Int32 OR Null      |
| enrollmentGrade2                                    | Int32 OR Null      |
| enrollmentGrade3                                    | Int32 OR Null      |
| enrollmentGrade4                                    | Int32 OR Null      |
| enrollmentGrade5                                    | Int32 OR Null      |
| enrollmentGrade6                                    | Int32 OR Null      |
| enrollmentGrade7                                    | Int32 OR Null      |
| enrollmentGrade8                                    | Int32 OR Null      |
| enrollmentGrade9                                    | Int32 OR Null      |
| enrollmentKindergarten                              | Int32 OR Null      |
| enrollmentTotal                                     | Int32 OR Null      |
| expendituresNonpersonnel                            | Decimal128 OR Null |
| farmStudentsEligibleForFreeOrReducedPriceLunch      | Int32 OR Null      |
| farmStudentsEligiblePercentage                      | Double OR Null     |
| fteAdministration                                   | Decimal128 OR Null |
| fteInstructionalAides                               | Decimal128 OR Null |
| fteSupportStaff                                     | Decimal128 OR Null |
| fteTeachers                                         | Int32 OR Null      |
| gradeRange                                          | String             |
| gradesOfferedHighest                                | String             |
| gradesOfferedLowest                                 | String             |
| isBureauOfIndianEducationSchool                     | Bool OR Null       |
| isCharter                                           | Bool OR Null       |
| isElementarySchool                                  | Bool               |
| isHighSchool                                        | Bool               |
| isMagnet                                            | Bool OR Null       |
| isMiddleSchool                                      | Bool               |
| isPrivate                                           | Bool OR Null       |
| isReligiousOrientation                              | Null               |
| isSharedTime                                        | Bool OR Null       |
| isTitleIEligible                                    | Bool               |
| isTitleISchoolWide                                  | Bool OR Null       |
| isUngradedSchool                                    | Bool OR Null       |
| isVirtual                                           | Bool OR Null       |
| latitude                                            | Double             |
| leaName                                             | Null OR String     |
| locationCity                                        | Null OR String     |
| locationStateAbbreviation                           | Null OR String     |
| locationStreet                                      | Null OR String     |
| locationZip                                         | Null OR String     |
| longitude                                           | Double             |
| mailingCity                                         | String             |
| mailingStateAbbreviation                            | String             |
| mailingStateName                                    | String             |
| mailingStreet                                       | String             |
| mailingZip                                          | String             |
| name                                                | String             |
| ncesLeaId                                           | String             |
| ncesUniqueId                                        | String             |
| percentTo4YearColleage                              | Null               |
| phone                                               | Null OR String     |
| privateSchoolAssociationName                        | Null               |
| privateSchoolAssociations                           | Array              |
| salariesAdministration                              | Decimal128 OR Null |
| salariesInstructionalAides                          | Decimal128 OR Null |
| salariesInstructionalStaff                          | Null               |
| salariesSupportStaff                                | Decimal128 OR Null |
| salariesTeachers                                    | Decimal128 OR Null |
| salariesTotal                                       | Decimal128 OR Null |
| schoolLevel                                         | Null OR String     |
| schoolStatus                                        | Null OR String     |
| schoolType                                          | Null OR String     |
| titleIStatus                                        | Null OR String     |
| urbanCentricLocale                                  | String             |

## Schema for US LEAs

(Local Education Agencies)

| Name                                  | Field Type         |
| ------------------------------------- | ------------------ |
| agencyCharterIndicator                | Null               |
| agencyLevel                           | String             |
| agencyType                            | String             |
| countyCode                            | String             |
| countyName                            | String             |
| dataCurrentAsOf                       | String             |
| enrollmentEnglishLanguageLearners     | Null               |
| enrollmentMigrantStudents             | Null               |
| enrollmentSped                        | Null               |
| enrollmentTotal                       | Int32              |
| expendituresGeneralAdministration     | Decimal128 \| Null |
| expendituresInstructionTotal          | Decimal128 \| Null |
| expendituresInstructionalStaff        | Decimal128 \| Null |
| expendituresSalariesTotal             | Decimal128 \| Null |
| expendituresSchoolAdministration      | Decimal128 \| Null |
| expendituresTechEquipment             | Decimal128 \| Null |
| expendituresTechSuppliesServices      | Decimal128 \| Null |
| expendituresTextbooks                 | Decimal128 \| Null |
| expendituresTotal                     | Decimal128 \| Null |
| financeDataCurrentAsOf                | Null \| String     |
| fteCoordinators                       | Decimal128 \| Null |
| fteInstructionalAides                 | Decimal128 \| Null |
| fteLeaAdministratorSupportStaff       | Decimal128 \| Null |
| fteLeaAdministrators                  | Decimal128 \| Null |
| fteLeaSchoolAdministratorSupportStaff | Decimal128 \| Null |
| fteLeaSchoolAdministrators            | Decimal128 \| Null |
| fteLeaStaffTotal                      | Decimal128 \| Null |
| fteSchoolStaffTotal                   | Decimal128 \| Null |
| fteStaffOther                         | Decimal128 \| Null |
| fteStaffTotal                         | Decimal128 \| Null |
| fteStudentSupportStaff                | Decimal128         |
| fteTeachersElementary                 | Decimal128 \| Null |
| fteTeachersSecondary                  | Decimal128 \| Null |
| fteTeachersTotal                      | Int32 \| Null      |
| fteTeachersUngraded                   | Decimal128 \| Null |
| gradeRange                            | String             |
| gradesOfferedHighest                  | String             |
| gradesOfferedLowest                   | String             |
| isBureauOfIndianEducation             | Bool               |
| latitude                              | Double             |
| locationCity                          | String             |
| locationState                         | String             |
| locationStreet                        | String             |
| locationZip                           | String             |
| locationZip4                          | String             |
| longitude                             | Double             |
| mailingCity                           | String             |
| mailingState                          | String             |
| mailingStateName                      | String             |
| mailingStreet                         | String             |
| mailingZip                            | String             |
| mailingZip4                           | String             |
| name                                  | String             |
| ncesUniqueId                          | String             |
| numberOfSchools                       | Int32              |
| phone                                 | String             |
| revenueTotal                          | Decimal128 \| Null |
| stateLeaId                            | String             |
| urbanCentricLocale                    | String             |
