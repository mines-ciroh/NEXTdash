# NEXTdash
Web dashboard to automatically retrieve and visualize TempEst-NEXT forecasts.

## Usage

This is meant to be hosted on GH pages or similar, but it will work as a plain HTML file.

However, if you open it through `file:///` (i.e., as an HTML file), OpenStreetMap will block the tiles because there is no user-agent string. The solution is to use an extension like UserAgentSwitcher and set a string that is not a browser UA.

## Data Source

The desired GeoJSON forecasts have URLs of the form:

https://www.hydroshare.org/resource/b8852529788a437a8d697e9b0435b99a/data/contents/full_forecasts/20260618_rawmap.json
