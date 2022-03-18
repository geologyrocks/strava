# strava-connector
This app will connect to my Stava account and listen out for new activity submissions.

Activities that have a property VirtualRide will have their gear changed to Kickr Snap.

Hide real rides that are less than a certain number of miles, maybe 3 or 4?  To catch those pootles around Eastleigh.  Also assign Commute tag.

Also set the basemap to Pride each time.

## Useful links:
* https://www.youtube.com/watch?v=sgscChKfGyg&ab_channel=franchyze923

TODO:
1. Check if .NET Standard 2.0 is good to be used still 
1. Add controller test file
1. Add appsettings with refreshToken secret
1. Build GET activities query with manual refresh token update
1. Setup automatic refresh token updates (check expiry?)
1. Manual / semi-automatic update of activities (`foreach` loop)
1. 
1. Try out webhooks
1. Webhooks
1. 