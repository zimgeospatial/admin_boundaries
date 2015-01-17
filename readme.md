##ABOUT ADMINISTRATIVE BOUNDARIES


1. Zimbabwe is divided into PROVINCES for administrative purposes. The provinces are subdivided into DISTRICTS which are further divided into WARDS. Read more on this structure from [Wikipedia](http://en.wikipedia.org/wiki/Subdivisions_of_Zimbabwe). 

2. This repository contains three(3) datasets pertaining administrative boundaries of Zimbabwe as polygon features. Please read on for data specific metadata. For general repository structure refer to this project's [Webpage](http://zimgeospatial.github.io/) which gives an explanation of other files in this repository. 

3. **This project has adopted the use of P-Codes ([explained here](http://geocode-encyclopedia.info/p_code)) to assign codes to the data. It is highly recommended that reference be made to the P-Codes 'dictionary' in the [reference repository.](https://gi♠thub.com/zimgeospatial/reference)** These are individual CSV files that can be sercahed within github.

4. The basis of the admin boundaries has been wards data [**admin_level3_wards.x**] as obtained from [humanitarianresponse](http://www.humanitarianresponse.info/operations/zimbabwe/dataset/zimbabwe-admin-level-3-boundaries) dated January 2008.

---
###NATIONAL [ admin_level0_country.x ]

####Summary
- Details the national boundary.

---
###PROVINCES [ admin_level1_provinces.x ]

####Summary
- Boundaries of the ten(10) provinces of Zimbabwe as polygon features.

####Field Definitions:

| Field Name        | Explanation          | 
| ------------- |-------------| 
| provincepc      | P-Code for the province. (Place Code) |
| province      | The name of the province      | 


---
###DISTRICTS [ admin_level2_districts.x ]

####Summary 
- Boundaries of the districts of Zimbabwe as polygon features.

####Field Definitions:
| Field Name        | Explanation          | 
| ------------- |-------------| 
| districtpc      | P-Code for the district. (Place Code) |
| district      | The name of the district      | 
| local_auth      | The name of the local authority      | 
| districtyp      | The type of the local authority      | 
| provincepc      | P-Code for the province. (Place Code) |

---
###WARDS [ admin_level3_wards.x ]

####Summary 
- Boundaries of the wards of Zimbabwe as polygon features.

####Field Definitions:
| Field Name    | Explanation                                      |
| ------------- | -------------                                    |
| wardpc        | P-Code for the ward. (Place Code)                |
| wardname      | The name of the ward which is actually a number. |
| province      | The name of the province                         |
| district      | The type of the district                         |
| alt_name     | Altenative district name.                        |
| districtpc        | P-Code for the district. (Place Code)                |
| provincepc        | P-Code for the province. (Place Code)                |
| integrity     | Changes made to the ward boundary as in year 2008|


---