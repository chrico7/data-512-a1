DATA 512 - A1
Corey Christopherson
10-3-2019


The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2019

###
## Source Data ##
###

Source data is licensed under the CC-BY-SA 3.0 and GFDL licenses
 - CC-BY-SA 3.0: https://creativecommons.org/licenses/by-sa/3.0/
 - GFDL: https://www.gnu.org/licenses/fdl-1.3.html

###
## API Documentation ##
###

Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

Legacy Pagecounts API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts

Pageviews API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

###
## Final Data Fields ##
###

en-wikipedia_traffic_200712-201809.csv

year                    | YYYY
month                   | MM
pagecount_all_views     | Legacy pagecount desktop + mobile views
pagecount_desktop_views | Legacy pagecount desktop views
pagecount_mobile_views  | Legacy pagecount mobile views
pageview_all_views      | Pageview desktop + mobile views
pageview_desktop_views  | Pageview desktop views
pageview_mobile_views   | Pageview mobile views (mobile-app + mobile-web)

###
## Special Considerations ##
###

 - Data from the Legacy Pagecount API includes webcrawlers while the data from the Pageview API does not
 - There is about one year of overlapping data between the two APIs in 2015/2016