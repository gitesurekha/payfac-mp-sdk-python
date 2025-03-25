CHANGELOG
---------
## 15.0.0
* **Feature** Support for Payfac MP API version 15.0 
+ Complex element -pciLevel of type pciLevelScore added in legalEntityCreateRequest
+ Complex element -pciLevel of type pciLevelScore added in legalEntityUpdateRequest
+ Complex elements-countryOfOrigin,revenueBoost,complianceProducts added in subMerchantCreateRequest 
+ Complex elements-countryOfOrigin,revenueBoost,complianceProducts added in subMerchantUpdateRequest
+ enum pciLevelScore with enum values 1,2,3,4 and enum complianceProductCode with values SAFERPAYMENT,OTHER
+ countryOfOrigin with type String with min and max length of 3
+ revenueBoost of type subMerchantRevenueBoostFeature
+ subMerchantRevenueBoostFeature of type boolean with enabled would be True/false
+ complianceProducts contain elements with their type:code of type complianceProductCode,name of type string,active of type boolean,activation  of type date
  ,deActivation of type date,complianceStatus of type string,complianceStatusDate of type date

## 14.0.0
* **Feature** Support for Payfac MP API version 14.0

## 13.1.0
* **Feature** Support for Payfac MP API version 13.1

## 13.0.0
* **Feature** Support for PayFac MP API version 13.0