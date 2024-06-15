# Raw data Wragling 

## Columns
'project_geographic_district'
'project_building_identifier'
'project_school_name', 'project_type'
'project_description',
'project_phase_name'
'project_status_name',
'project_phase_actual_start_date'
'project_phase_planned_end_date'
'project_phase_actual_end_date'
'project_budget_amount',
'final_estimate_of_actual_costs_through_end_of_phase_amount'
'total_phase_actual_spending_amount'
'dsf_number_s'

# Missing Values Identification 

From a for loop function we find for if the columns provides a NaN includes
- project_phase_name
- project_phase_actual_end_date
- final_estimate_of_actual_costs_through_end_of_phase_amount

From a for loop function we find for columns including a null:
- project_phase_name
- final_estimate_of_actual_costs_through_end_of_phase_amount

# What to do about missing values?
Clearly project name doesnt have a factor on the learning decision thus can be removed, project_phase_name.

# Project Status
Many values have PNS 
(1) If project has end and start date then -> trasnform into complete
    Cases (1) Has end and start data of planned/actual -> complete
    Case (2) Has end but not start then -> complete
    Case (3) has end dat

## Project goegraphic distrcit 
all inputs are intergers

## project building identifier
checking if the building code follows structure "M123" 
Not in correct form:
Index: 1479 Value: XAAF
Index: 1480 Value: XADJ
Index: 1481 Value: XADO
Index: 1482 Value: XADY
Index: 1483 Value: XAEE
Index: 2606 Value: XABI
Index: 2607 Value: XAEO
Index: 2608 Value: XAFB
Index: 2609 Value: XAUJ
Index: 5504 Value: QALP
Index: 5505 Value: QAPM
Index: 6089 Value: QMAD
Index: 6218 Value: KBZT
Index: 6219 Value: KBZT
Index: 6220 Value: KBZT
Index: 6221 Value: KBZT
Index: 6909 Value: KAKB
Index: 6910 Value: KAKB
Index: 6911 Value: KAKB
Index: 6912 Value: KAKB


# Dates Validity Check
is the dates is valid?



