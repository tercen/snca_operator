# sNCA operator

#### Description
`snca` operator calculates a single non compartamental model for a dose/time series.


##### Usage
Input projection|.
---|---
`col` | 1st factor is the dose(mg)
`y-axis`| is the value of the serum maker
`x-axis`| is the time(hrs)


Output relations|.
---|---
TMAX_h|
CMAX_ng_per_ml|
LAMZHL_h|
AUC_0_4h_ng_per_ml|
AUC_0_8h_ng_per_ml|
AUC_0_12h_ng_per_ml|
AUC_4_24h_ng_per_ml|
AUC_0_24h_ng_per_ml|

##### Details
`snca` operator estimates Glomerular filtration rate (GFR) is the best overall index of kidney function.
Four equations are used to calculate four eGFR values.


#### References
 
ref for equation 0: [https://www.kidney.org/professionals/kdoqi/gfr_calculator]


##### See Also


#### Examples
