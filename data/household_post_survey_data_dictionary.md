# Household Customers Post-Survey - Data Dictionary

## Identification and Basic Information
- `id_anonymized`: Unique identifier for each household, anonymized
- `community_anonymized`: Community identifier, anonymized
- `interviewed_before`: Indicator if household was previously interviewed
- `connection_period`: Duration of connection to mini-grid
- `country`: Country location of household

## Demographic Information
- `age`: Age of respondent
- `gender`: Gender of respondent
- `household_headcount_change`: Changes in household size
- `household_headcount_change_explain`: Explanation of household size changes
- `avg_person_age_water_collection`: Average age of person responsible for water collection

## Economic Indicators
- `occupation_change`: Changes in occupation
- `occupation_change_explain`: Explanation of occupation changes
- `household_income_change`: Changes in household income
- `household_income_change_explain`: Explanation of income changes
- `avg_household_income`: Average household income

## Education
- `girls_schooling_change`: Changes in girls' school attendance
- `boys_schooling_change`: Changes in boys' school attendance
- `school_performance_change`: Changes in school performance
- `school_performance_change_explain`: Explanation of school performance changes
- `girls_unschooled_reasons`: Reasons for girls not attending school
- `girls_unschooled_reasons_explain`: Detailed explanation of girls' non-attendance in school
- `boys_unschooled_reasons`: Reasons for boys not attending school
- `boys_unschooled_reasons_explain`: Detailed explanation of boys' non-attendance in school
- `water_collection_school_aged`: Indicator if school-aged children collect water

## Business Activities
- `household_business_owners`: Number of business owners in household
- `business_owners_count`: Count of business owners
- `business_owners_binary`: Binary indicator of business ownership
- `business_owners_female`: Count of female business owners
- `business_type`: Type of business
- `business_recent`: Indicator if business is recently established
- `business_from_minigrid`: Business established due to mini-grid access
- `business_use_minigrid`: Business uses mini-grid power

## Power and Energy Usage
- `power_sources`: Sources of power used
- `power_primary_source_explain`: Explanation of primary power source
- `power_sources_usage`: Usage patterns of different power sources
- `power_sources_primary`: Primary source of power
- `power_current_sources_explain`: Explanation of current power sources
- `power_sources_unclean`: Unclean power sources used
- `power_sources_primary_unclean`: Primary unclean power source

## Appliances and Technology
- `appliances_count`: Total number of appliances
- `appliances_count_change`: Change in appliance count
- `cellphones_count`: Number of cellphones
- `appliances_type`: Types of appliances owned
- `appliances_explain`: Explanation of appliance usage
- `appliances_type_addition`: Types of appliances added
- `appliances_addition_explain`: Explanation of appliance additions
- `appliances_addition_count`: Count of new appliances added

## Lighting
- `light_hours_current`: Current hours of lighting
- `light_primary_sources`: Primary sources of lighting
- `light_primary_sources_unclean`: Unclean lighting sources used
- `community_lights`: Presence of community lighting
- `home_exterior_lights`: Presence of exterior home lighting
- `exterior_lights_minigrid`: Exterior lighting powered by mini-grid

## Kerosene Usage
- `kerosene_lamp_usage_change`: Changes in kerosene lamp usage
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

## Water Access
- `water_source`: Source of water
- `clean_drinking_water`: Access to clean drinking water
- `clean_drinking_water_source`: Source of clean drinking water
- `community_clean_water_source`: Community water source
- `water_collection_travel_distance`: Distance traveled for water collection
- `water_collection_time`: Time spent collecting water
- `water_collection_responsible`: Person responsible for water collection
- `water_collection_responsible_binary`: Binary indicator of water collection responsibility
- `water_cost`: Cost of water

## Healthcare Access
- `clinic_travel_distance`: Distance to nearest clinic
- `clinic_electricity_access`: Clinic access to electricity
- `clinic_open_hours`: Clinic operating hours
- `clinic_refrigeration_access`: Clinic access to refrigeration
- `better_access_health_minigrid`: Improved healthcare access due to mini-grid

## Safety and Security
- `feel_safe_dark`: Feeling of safety in darkness
- `feel_safe_if_exterior_lights`: Feeling of safety with exterior lighting
- `feel_unsafe_reasons`: Reasons for feeling unsafe
- `feel_unsafe_reasons_explain`: Detailed explanation of safety concerns
- `feel_safer_with_minigrid`: Increased safety feeling with mini-grid
- `i_dont_feel_unsafe`: Indicator of feeling safe
- `unsafe_due_to_theft`: Safety concerns due to theft
- `unsafe_due_to_unsafe_travel`: Safety concerns due to travel
- `unsafe_due_to_lack_of_community_lighting`: Safety concerns due to lack of lighting

## Mini-grid Impact
- `minigrid_benefits`: Benefits from mini-grid access
- `minigrid_access_life_improvement`: Life improvements from mini-grid access
- `minigrid_access_life_improvement_explain`: Explanation of life improvements
- `minigrid_access_life_family_impact`: Impact on family life
- `minigrid_access_productivity_improvement`: Productivity improvements
- `minigrid_effect_on_household_female`: Impact on female household members

## Consumption and Payment Metrics
- `Sum.of.kWh.Consumed.x`: Total kilowatt-hours consumed (first measure)
- `Total.Payment..Local.`: Total payments in local currency
- `avg_mon_consumption_period`: Average monthly consumption during period
- `Sum.of.kWh.Consumed.y`: Total kilowatt-hours consumed (second measure)
- `Sum.of.Net.Payment.Amount..Local.`: Net payment amount in local currency
- `avg_mon_consumption_cum`: Cumulative average monthly consumption
