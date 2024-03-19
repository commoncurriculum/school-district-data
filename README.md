# school-district-data
Exports from urban.org


# Schema for Schools
|Name                                                         |Field Type|
|-------------------------------------------------------------|----------|
|_id (nces school id)                                         |String    |
|cbsa                                                         |String    |
|congress_district_id                                         |Int32     |
|county_code                                                  |String    |
|csa                                                          |String    |
|data_current_as_of                                           |Int32     |
|enrollment_kindergarten                                      |Int32     |
|enrollment_grade_1                                           |Int32     |
|enrollment_grade_2                                           |Int32     |
|enrollment_grade_3                                           |Int32     |
|enrollment_grade_4                                           |Int32     |
|enrollment_grade_5                                           |Int32     |
|enrollment_grade_6                                           |Int32     |
|enrollment_grade_7                                           |Int32     |
|enrollment_grade_8                                           |Int32     |
|enrollment_grade_9                                           |Int32     |
|enrollment_grade_10                                          |Int32     |
|enrollment_grade_11                                          |Int32     |
|enrollment_grade_12                                          |Int32     |
|enrollment_total                                             |Int32     |
|enrollment_ungraded                                          |Int32     |
|expenditures_nonpersonnel                                    |String    |
|farm_students_eligible_for_free_lunch                        |Int32     |
|farm_students_eligible_for_free_lunch_by_direct_certification|Int32     |
|farm_students_eligible_for_free_or_reduced_price_lunch       |Int32     |
|farm_students_eligible_for_reduced_price_lunch               |Int32     |
|farm_students_eligible_percentage                            |Double    |
|fips                                                         |Int32     |
|fips_label                                                   |String    |
|fte_administration                                           |String    |
|fte_instructional_aides                                      |String    |
|fte_support_staff                                            |String    |
|fte_teachers                                                 |Int32     |
|grade_range                                                  |String    |
|grades_offered_highest                                       |String    |
|grades_offered_lowest                                        |String    |
|is_bureau_of_indian_education_school                         |Bool      |
|is_charter                                                   |Bool      |
|is_elementary_school                                         |Bool      |
|is_high_school                                               |Bool      |
|is_magnet                                                    |Bool      |
|is_middle_school                                             |Bool      |
|is_shared_time                                               |Bool      |
|is_title_i_elibile                                           |Bool      |
|is_title_i_school_wide                                       |Bool      |
|is_ungraded_school                                           |Bool      |
|is_virtual                                                   |Bool      |
|latitude                                                     |Double    |
|lea_id_nces                                                  |String    |
|lea_name                                                     |String    |
|location_city                                                |String    |
|location_state                                               |String    |
|location_street                                              |String    |
|location_zip                                                 |String    |
|longitude                                                    |Double    |
|lunch_program                                                |String    |
|mailing_city                                                 |String    |
|mailing_state                                                |String    |
|mailing_street                                               |String    |
|mailing_zip                                                  |String    |
|ncessch                                                      |String    |
|phone                                                        |String    |
|salaries_administration                                      |String    |
|salaries_instructional_aides                                 |String    |
|salaries_instructional_staff                                 |Null      |
|salaries_support_staff                                       |String    |
|salaries_teachers                                            |Int32     |
|salaries_total                                               |String    |
|school_id_nces                                               |String    |
|school_id_state                                              |String    |
|school_level                                                 |String    |
|school_name                                                  |String    |
|school_status                                                |String    |
|school_type                                                  |String    |
|state_lea_id                                                 |String    |
|state_leg_district_lower                                     |String    |
|state_leg_district_upper                                     |String    |
|student_enrollment                                           |Int32     |
|title_i_status                                               |String    |
|urban_centric_locale                                         |String    |


# Schema for Districts
|name                                                         |field_type|
|-------------------------------------------------------------|----------|
|_id (lea_id from nces)                                       |String    |
|agency_charter_indicator                                     |Null      |
|agency_level                                                 |String    |
|agency_type                                                  |String    |
|assets_bond_fund                                             |Int32     |
|assets_other                                                 |Int32     |
|assets_sinking_fund                                          |Int32     |
|benefits_employee_instruction                                |Int32     |
|benefits_employee_total                                      |Int32     |
|benefits_enterprise_operations                               |Int32     |
|benefits_food_service                                        |Int32     |
|benefits_supp_bco                                            |Double    |
|benefits_supp_general_admin                                  |Int32     |
|benefits_supp_instruc_staff                                  |Int32     |
|benefits_supp_operation_plant                                |Int32     |
|benefits_supp_pupils                                         |Double    |
|benefits_supp_sch_admin                                      |Double    |
|benefits_supp_stud_transport                                 |Int32     |
|boundary_change_indicator                                    |String    |
|cbsa                                                         |Int32     |
|censusid                                                     |String    |
|cmsa                                                         |Null      |
|congress_district_id                                         |Int32     |
|county_code                                                  |String    |
|county_name                                                  |String    |
|csa                                                          |Int32     |
|data_current_as_of                                           |Int32     |
|debt_interest                                                |Int32     |
|debt_longterm_issued_fy                                      |Int32     |
|debt_longterm_outstand_beg_fy                                |Int32     |
|debt_longterm_outstand_end_fy                                |Int32     |
|debt_longterm_retired_fy                                     |Int32     |
|debt_shortterm_outstand_beg_fy                               |Int32     |
|debt_shortterm_outstand_end_fy                               |Int32     |
|enrollment_english_language_learners                         |Null      |
|enrollment_fall_responsible                                  |Int32     |
|enrollment_fall_school                                       |Int32     |
|enrollment_migrant_students                                  |Null      |
|enrollment_sped                                              |Null      |
|enrollment_total_students                                    |Int32|
|exp_current_arra                                             |Null      |
|exp_current_bco                                              |Double    |
|exp_current_elsec_total                                      |Int32     |
|exp_current_enterprise                                       |Int32     |
|exp_current_federal_funds                                    |Int32     |
|exp_current_food_serv                                        |Int32     |
|exp_current_general_admin                                    |Int32     |
|exp_current_instruc_staff                                    |Int32     |
|exp_current_instruction_total                                |Int32     |
|exp_current_operation_plant                                  |Int32     |
|exp_current_other                                            |Int32     |
|exp_current_other_elsec                                      |Int32     |
|exp_current_pupils                                           |Int32     |
|exp_current_resa                                             |Double    |
|exp_current_sch_admin                                        |Int32     |
|exp_current_state_local_funds                                |Int32     |
|exp_current_student_transport                                |Int32     |
|exp_current_supp_serv_nonspec                                |Int32     |
|exp_current_supp_serve_total                                 |Int32     |
|exp_nonelsec                                                 |Int32     |
|exp_nonelsec_adult_education                                 |Int32     |
|exp_nonelsec_community_serv                                  |Int32     |
|exp_nonelsec_other                                           |Int32     |
|exp_tech_equipment                                           |Int32     |
|exp_tech_supplies_services                                   |Int32     |
|exp_textbooks                                                |Int32     |
|exp_total                                                    |Int32     |
|exp_utilities_energy                                         |Int32     |
|finance_data_current_as_of                                   |Int32     |
|fips                                                         |Int32     |
|fips_label                                                   |String    |
|fte_coordinators                                             |Int32|
|fte_guidance_counselors_elem                                 |Int32|
|fte_guidance_counselors_other                                |Null      |
|fte_guidance_counselors_sec                                  |Int32|
|fte_instructional_aids                                       |Int32|
|fte_lea_administrator_support_staff                          |Int32|
|fte_lea_administrators                                       |Int32|
|fte_lea_staff_total                                          |Int32|
|fte_librarian_specialists                                    |Int32|
|fte_librarian_support_staff                                  |Int32|
|fte_school_administrator_support_staff                       |Int32|
|fte_school_administrators                                    |Int32|
|fte_school_counselors                                        |Double|
|fte_school_psychologists                                     |Double|
|fte_school_staff_total                                       |Double|
|fte_staff_other                                              |Double|
|fte_staff_total                                              |Int32|
|fte_student_support_staff                                    |Int32     |
|fte_student_support_without_psychologists                    |Double|
|fte_support_staff_other                                      |Int32|
|fte_teachers_elementary                                      |Int32|
|fte_teachers_kindergarten                                    |Int32|
|fte_teachers_prek                                            |Int32|
|fte_teachers_secondary                                       |Int32|
|fte_teachers_total                                           |Int32|
|fte_teachers_ungraded                                        |Int32|
|grade_range                                                  |String    |
|grades_offered_highest                                       |String    |
|grades_offered_lowest                                        |String    |
|is_bureau_of_indian_education                                |Bool      |
|latitude                                                     |Double    |
|lea_id_nces                                                  |String    |
|lea_name                                                     |String    |
|leaid                                                        |String    |
|location_city                                                |String    |
|location_state                                               |String    |
|location_street                                              |String    |
|location_zip                                                 |String    |
|location_zip4                                                |String    |
|longitude                                                    |Double    |
|mailing_city                                                 |String    |
|mailing_state                                                |String    |
|mailing_street                                               |String    |
|mailing_zip                                                  |String    |
|mailing_zip4                                                 |String    |
|necta                                                        |Int32     |
|number_of_schools                                            |Int32     |
|outlay_capital_arra                                          |Null      |
|outlay_capital_construction                                  |Int32     |
|outlay_capital_instruc_equip                                 |Int32     |
|outlay_capital_land_structures                               |Int32     |
|outlay_capital_nonspec_equip                                 |Int32     |
|outlay_capital_other_equip                                   |Int32     |
|outlay_capital_total                                         |Int32     |
|payments_charter_schools                                     |Double    |
|payments_local_govt                                          |Int32     |
|payments_other_sch_system                                    |Int32     |
|payments_private_schools                                     |Double    |
|payments_state_govt                                          |Int32     |
|phone                                                        |String    |
|rev_fed_arra                                                 |Null      |
|rev_fed_child_nutrition_act                                  |Int32     |
|rev_fed_direct_impact_aid                                    |Int32     |
|rev_fed_direct_indian_ed                                     |Int32     |
|rev_fed_direct_other                                         |Int32     |
|rev_fed_nonspec                                              |Int32     |
|rev_fed_state_bilingual_ed                                   |Int32     |
|rev_fed_state_drug_free                                      |Int32     |
|rev_fed_state_idea                                           |Int32     |
|rev_fed_state_math_sci_teach                                 |Int32     |
|rev_fed_state_other                                          |Int32     |
|rev_fed_state_title_i                                        |Int32     |
|rev_fed_state_vocational                                     |Int32     |
|rev_fed_total                                                |Double    |
|rev_local_cities_counties                                    |Int32     |
|rev_local_dist_activ_receipts                                |Int32     |
|rev_local_fines_forfeits                                     |Int32     |
|rev_local_income_tax                                         |Int32     |
|rev_local_interest_earnings                                  |Int32     |
|rev_local_misc                                               |Int32     |
|rev_local_oth_sales_serv                                     |Int32     |
|rev_local_other_sch_systems                                  |Int32     |
|rev_local_other_tax                                          |Int32     |
|rev_local_parent_govt                                        |Int32     |
|rev_local_private_contrib                                    |Int32     |
|rev_local_prop_tax                                           |Int32     |
|rev_local_property_sale                                      |Int32     |
|rev_local_rents_royalties                                    |Int32     |
|rev_local_sales_tax                                          |Int32     |
|rev_local_sch_lunch                                          |Int32     |
|rev_local_student_fees_nonspec                               |Int32     |
|rev_local_textbook_sales_rents                               |Int32     |
|rev_local_total                                              |Int32     |
|rev_local_transportation_fees                                |Int32     |
|rev_local_tuition_fees                                       |Int32     |
|rev_local_utility_tax                                        |Int32     |
|rev_nces                                                     |Int32     |
|rev_state_bilingual_ed                                       |Int32     |
|rev_state_compens_basic_ed                                   |Int32     |
|rev_state_employee_benefits                                  |Int32     |
|rev_state_gen_formula_assist                                 |Double    |
|rev_state_gifted_talented                                    |Int32     |
|rev_state_nonspec                                            |Int32     |
|rev_state_not_employee_benefits                              |Int32     |
|rev_state_oth_prog                                           |Double    |
|rev_state_outlay_capital_debt                                |Int32     |
|rev_state_sch_lunch                                          |Int32     |
|rev_state_special_ed                                         |Int32     |
|rev_state_staff_improve                                      |Int32     |
|rev_state_total                                              |Double    |
|rev_state_transportation                                     |Int32     |
|rev_state_vocational_ed                                      |Int32     |
|rev_total                                                    |Double    |
|salaries_food_service                                        |Int32     |
|salaries_instruction                                         |Int32     |
|salaries_supp_bco                                            |Double    |
|salaries_supp_general_admin                                  |Int32     |
|salaries_supp_instruc_staff                                  |Int32     |
|salaries_supp_operation_plant                                |Int32     |
|salaries_supp_pupils                                         |Int32     |
|salaries_supp_sch_admin                                      |Int32     |
|salaries_supp_stud_transport                                 |Int32     |
|salaries_teachers_other_ed                                   |Int32     |
|salaries_teachers_regular_prog                               |Int32     |
|salaries_teachers_sped                                       |Int32     |
|salaries_teachers_vocational                                 |Int32     |
|salaries_total                                               |Int32     |
|state_lea_id                                                 |String    |
|state_leg_district_lower                                     |String    |
|state_leg_district_upper                                     |String    |
|urban_centric_locale                                         |String    |
