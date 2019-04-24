Packet Clearing House Daily Routing Snapshots Scraper

PCH provides daily BGP routing snapshot since 2001. However, the website directory structure changes over time.
This script aims to list all available MTR files by overcoming this odd website structure.

Input: year or list of years
       the year that you would like to get he MRT files
Output: 
      list of directories where all files from that year can be downloaded

Example:

```
---working in year: 2008 ---
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2008/
---working in year: 2009 ---
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/03
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/04
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/05
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/06
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/07
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/08
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/09
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/10
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/11
http://www.pch.net/resources/Routing_Data/IPv4_daily_snapshots/2009/12
