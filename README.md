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
`eGFR_0`| numeric, equation 0 calculation of the GFR estimate (e.g. per cell)
`eGFR_1`| numeric, equation 1 calculation of the GFR estimate (e.g. per cell)
`eGFR_2`| numeric, equation 2 calculation of the GFR estimate (e.g. per cell)
`eGFR_3`| numeric, equation 3 calculation of the GFR estimate (e.g. per cell)

##### Details
`snca` operator estimates Glomerular filtration rate (GFR) is the best overall index of kidney function.
Four equations are used to calculate four eGFR values.


#### References
 
ref for equation 0: [https://www.kidney.org/professionals/kdoqi/gfr_calculator]


##### See Also


#### Examples
