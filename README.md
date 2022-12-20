# roberthalf.com Google Maps API key leaked

hi team,

[!] Google API key leaked via Page Source
[!] any persons can use this api key for their own use


api key: AIzaSyDnJ9P3666KIhgb9fjstivsiTNbGM4zjMA

API key is ← vulnerable ← for Geocode API! BOOM! Here is the Link
https://maps.googleapis.com/maps/api/geocode/json?latlng=40,30&key=AIzaSyDnJ9P3666KIhgb9fjstivsiTNbGM4zjMA

API key is ← vulnerable ← for Find Place From Text API! BOOM! Here is the Link
https://maps.googleapis.com/maps/api/place/findplacefromtext/json?input=Museum%20of%20Contemporary%20Art%20Australia&inputtype=textquery&fields=photos,formatted_address,name,rating,opening_hours,geometry&key=AIzaSyDnJ9P3666KIhgb9fjstivsiTNbGM4zjMA

API key is ← vulnerable ← for Autocomplete API! BOOM! Here is the Link
https://maps.googleapis.com/maps/api/place/autocomplete/json?input=Bingh&types=%28cities%29&key=AIzaSyDnJ9P3666KIhgb9fjstivsiTNbGM4zjMA

Results:
- Geocode
- Find Place From Text
- Autocomplete


impac:
[!] costing companies extra money and in some cases DOS.
[!] we can bypass rate limit by using proxy list. 

Resources:
[-] https://hackerone.com/reports/724039
[-] https://hackerone.com/reports/1065041



















