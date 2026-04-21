# WBOPENDATA: Stata module to access World Bank databases

W minor patches:

```stata
net install wbopendata, from("https://raw.githubusercontent.com/asjadnaqvi/wbopendata/main/src") replace
```


Fork of [https://github.com/jpazvd/wbopendata](https://github.com/jpazvd/wbopendata)

NOTES: 

- WB OpenData API has moved quite a lot of indicators offline. Replication of files from a year ago is no longer possible. 

- Some indicators exist in the API metadata endpoint but do not return downloadable data from the data endpoint.


