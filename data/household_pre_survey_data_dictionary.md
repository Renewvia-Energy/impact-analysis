# Household Customers Pre-Survey - Data Dictionary

## Identification and Basic Demographics
- `id_anonymized`: Unique identifier for each household, anonymized
- `community_anonymized`: Community identifier, anonymized
- `country`: Country location of household
- `age`: Age of respondent
- `gender`: Gender of respondent
- `end_date`: Survey completion date

## Household Composition
- `household_headcount`: Total number of household members
- `adult_headcount`: Number of adults in household
- `girls_headcount`: Number of girls in household
- `boys_headcount`: Number of boys in household
- `girls_age`: Ages of girls in household
- `boys_age`: Ages of boys in household

## Economic Status
- `occupation`: Respondent's occupation
- `occupation_primary_explain`: Detailed explanation of primary occupation
- `primary_provider`: Primary income provider indicator
- `primary_provider_occupation`: Occupation of primary provider
- `occupation_secondary_provider`: Secondary income provider indicator
- `occupation_secondary_explain`: Explanation of secondary income source
- `employement_type`: Type of employment
- `avg_household_income`: Average household income

## Education
- `girls_schooling`: School attendance status for girls
- `girls_unschooled_reasons`: Reasons for girls not attending school
- `girls_unschooled_reasons_explain`: Detailed explanation of girls' non-attendance
- `boys_schooling`: School attendance status for boys
- `boys_unschooled_reasons`: Reasons for boys not attending school
- `boys_unschooled_reasons_explain`: Detailed explanation of boys' non-attendance

## Business Activities
- `household_business_owners`: Number of business owners in household
- `business_owners_count`: Count of business owners
- `business_owners_binary`: Binary indicator of business ownership
- `business_owners_female`: Count of female business owners

## Mini-grid Usage
- `minigrid_signup_primary_reason`: Primary reason for mini-grid subscription
- `minigrid_signup_secondary_reason`: Secondary reason for mini-grid subscription

## Power and Energy Usage
- `power_sources`: Sources of power used
- `power_current_sources_explain`: Explanation of current power sources
- `power_sources_usage`: Usage patterns of different power sources
- `power_sources_primary`: Primary source of power
- `power_primary_source_explain`: Explanation of primary power source
- `power_sources_unclean`: Unclean power sources used
- `power_sources_primary_unclean`: Primary unclean power source

## Appliances and Technology
- `appliances_count`: Total number of appliances
- `appliances_type_count`: Count of different appliance types
- `cellphones_count`: Number of cellphones
- `appliances_type`: Types of appliances owned
- `appliances_explain`: Explanation of appliance usage
- `appliances_addition_type`: Types of appliances added
- `appliances_addition_explain`: Explanation of appliance additions

## Lighting
- `light_hours_current`: Current hours of lighting
- `light_primary_sources`: Primary sources of lighting
- `light_primary_sources_unclean`: Unclean lighting sources used
- `community_lights`: Presence of community lighting
- `home_exterior_lights`: Presence of exterior home lighting

## Kerosene Usage
- `kerosene_lamps_count`: Number of kerosene lamps
- `kerosene_lamp_usage_time`: Duration of kerosene lamp usage
- `kerosene_lamps_cost`: Cost of kerosene lamps

## Cooking Energy
- `cooking_energy_sources`: Sources of cooking energy
- `cooking_energy_sources_explain`: Explanation of cooking energy sources
- `cooking_energy_sources_unclean`: Unclean cooking energy sources
- `cooking_fuel_collection_time`: Time spent collecting cooking fuel
- `cooking_fuel_responsible`: Person responsible for fuel collection
- `cooking_fuel_responsible_binary`: Binary indicator of fuel collection responsibility
- `cooking_energy_cost`: Cost of cooking energy

## Device Charging
- `applicances_charging_sources`: Sources for charging appliances
- `applicances_charging_sources_explain`: Explanation of charging sources
- `applicances_charging_cost`: Cost of charging appliances
- `applicances_charging_sources_unclean`: Unclean charging sources
- `phone_charge_location`: Location where phones are charged
- `phone_charge_location_explain`: Explanation of phone charging location
- `phone_charge_frequency`: Frequency of phone charging
- `phone_charge_cost`: Cost of phone charging
- `phone_charge_travel_distance`: Distance traveled for phone charging

## Safety and Security
- `feel_safe_dark`: Feeling of safety in darkness
- `feel_safe_if_exterior_lights`: Feeling of safety with exterior lighting
- `feel_unsafe_reasons`: Reasons for feeling unsafe
- `feel_unsafe_reasons_explain`: Detailed explanation of safety concerns
- `i_dont_feel_unsafe`: Indicator of feeling safe
- `unsafe_due_to_theft`: Safety concerns due to theft
- `unsafe_due_to_unsafe_travel`: Safety concerns due to travel
- `unsafe_due_to_lack_of_community_lighting`: Safety concerns due to lack of lighting

## Water Access
- `water_source`: Source of water
- `clean_drinking_water`: Access to clean drinking water
- `clean_drinking_water_source`: Source of clean drinking water
- `clean_water_source`: Type of clean water source
- `community_clean_water_source`: Community water source
- `water_collection_travel_distance`: Distance traveled for water collection
- `water_collection_time`: Time spent collecting water
- `water_collection_responsible`: Person responsible for water collection
- `water_collection_responsible_binary`: Binary indicator of water collection responsibility
- `water_collection_school_aged`: Indicator if school-aged children collect water
- `avg_person_age_water_collection`: Average age of person responsible for water collection
- `water_cost`: Cost of water

## Healthcare Access
- `clinic_travel_distance`: Distance to nearest clinic
- `clinic_electricity_access`: Clinic access to electricity
- `clinic_open_hours`: Clinic operating hours
- `clinic_refrigeration_access`: Clinic access to refrigeration

## Other
- `other_household_activities`: Other activities conducted in household
