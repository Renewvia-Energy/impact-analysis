# Commercial & Institution Customers Survey - Data Dictionary

## Identification Variables
- `id_anonymized`: Unique identifier for each record, anonymized for privacy
- `community_anonymized`: Name or identifier of the community, anonymized
- `country`: Country where the mini-grid is located
- `original_person`: Indicator for whether the respondent is the original subscriber
- `first_name`: First name of the respondent
- `last_name`: Last name of the respondent

## Business Information
- `business_type`: Category or type of business
- `institution_name`: Name of the institution or business
- `operation_status`: Current operational status of the business
- `closed_operations_explain`: Explanation if operations have ceased
- `connection_period`: Duration of connection to the mini-grid
- `connection_period_non_original_subscriber`: Connection duration for non-original subscribers

## Energy Usage and Changes
- `non_renewvia_electrical_sources`: Non-renewable electrical sources used
- `kerosene_usage_change`: Changes in kerosene consumption after mini-grid connection
- `diesel_usage_change`: Changes in diesel consumption after mini-grid connection
- `operations_hours_change`: Changes in operational hours
- `business_hours_increase`: Increase in business hours after connection

## Appliances and Infrastructure
- `appliances_addition_type`: Types of appliances added after connection
- `appliances_addition_explain`: Explanation of appliance additions
- `appliances_addition_count`: Number of new appliances added
- `clean_drinking_water_access`: Access to clean drinking water

## Business Impact
- `ci_offering_change`: Changes in commercial/industrial offerings
- `new_prod_serv_add_explain`: Explanation of new products/services added
- `workforce_change`: Changes in workforce size
- `workforce_change_explain`: Explanation of workforce changes
- `workforce_change_female`: Changes in female workforce
- `earnings_change`: Changes in business earnings
- `ci_new_offering`: New commercial/industrial offerings

## Health Services Impact
- `health_offering_change`: Changes in health service offerings
- `clinic_offering_unable_prior_minigrid`: Health services previously unavailable before mini-grid
- `health_offering_change_count`: Count of new health services offered
- `clinic_longer_hours`: Extension of clinic operating hours
- `vaccine_cold_storage`: Availability of vaccine cold storage
- `more_patients_treated`: Increase in patient treatment capacity
- `shorter_wait`: Reduction in patient wait times

## Education Impact
- `school_attendance_change`: Changes in school attendance
- `school_offering_unable_prior_minigrid`: Educational services previously unavailable before mini-grid
- `school_performance`: Changes in school performance

## General Impact
- `minigrid_benefits`: Benefits observed from mini-grid connection
- `minigrid_problems`: Problems or challenges with mini-grid connection

## Consumption and Payment Metrics
- `Sum.of.kWh.Consumed.x`: Total kilowatt-hours consumed during specific pre-post survey period
- `Total.Payment..Local.`: Total payments in local currency (Naira or Ksh)
- `avg_mon_consumption_period`: Average monthly consumption during specific pre-post survey period
- `Sum.of.kWh.Consumed.y`: Total kilowatt-hours consumed all periods until report date
- `Sum.of.Net.Payment.Amount..Local.`: Net payment amount in local currency (Naira or Ksh)
- `avg_mon_consumption_cum`: Average monthly consumption all periods until report date
