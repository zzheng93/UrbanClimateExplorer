## How to create a json file?

```
{
"city_loc": {"lat": 40.1164, "lon": -88.2434}, 
"catalog_url": "https://raw.githubusercontent.com/NCAR/cesm-lens-aws/main/intake-catalogs/aws-cesm1-le.json", 
"l_component": "lnd",
"a_component": "atm",
"experiment": "RCP85",
"frequency": "daily",
"cam_ls": ["TREFHT", "TREFHTMX", "FLNS", "FSNS", "PRECSC", "PRECSL", "PRECT", "QBOT", "UBOT", "VBOT"], 
"clm_ls": ["TREFMXAV_U"], 
"time_start": "2081-01-02", 
"time_end": "2100-12-31", 
"member_id": [2], 
"estimator_list": ["lgbm", "xgboost", "rf", "extra_tree"], 
"time_budget": 15, 
"features": ["FLNS", "FSNS", "PRECT", "PRSN", "QBOT", "TREFHT", "UBOT", "VBOT"], 
"label": ["TREFMXAV_U"]
}
```
