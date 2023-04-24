# Find Places

Here is an example of a CrossCompute Tool that returns a list of places given a description and a location, such as "Hospitals in New York, NY, USA." You will need to enable the Google Places API and export your Google API key to the GOOGLE_KEY environment variable to deploy this tool.

```bash
pip install crosscompute>=0.9.4 crosscompute-views-map>=0.2.0
git clone https://github.com/crosscompute/find-places
cd find-places
bash setup.sh
export GOOGLE_KEY=YOUR-GOOGLE-KEY
crosscompute
```
