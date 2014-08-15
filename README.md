Snapshots
=========

Source code for www.csc.noaa.gov/snapshots as of 2014-08-12

If you try to run it on your computer outside NOS network it will not work. You'll need to update /Services/SharedService.js so variables argis and snapshtos are like this:

      argis = "http://maps.csc.noaa.gov/arcgis/rest/services/Snapshot/";
      snapshots = "http://csc.noaa.gov/dataservices/Snapshot/v2/";

Feel free to submit an issue in GitHub.

Good luck!
