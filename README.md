# timestamp-reflectors
A list of IP addresses that respond to ICMP type 13 (timestamp) requests, in CSV format.

According to <a href='https://datatracker.ietf.org/doc/html/rfc792'>RFC 792</a> (page 17), timestamps in ICMP type 13 messages should describe the number of milliseconds since midnight UTC, but some reflectors don't follow this requirement. Some reflectors respond with random nonsensical values - these reflectors are not included in the lists. Other reflectors return usable timestamps, but they are significantly offset from number-of-milliseconds-since-midnight-UTC by a consistent amount. Each reflector's offset is included in the lists.

The subdirectories contain CSV files organised by location, with the granularity and accuracy depending on what data was available from <a href='https://dev.maxmind.com/geoip/geolite2-free-geolocation-data/'>Maxmind</a>, <a href='https://db-ip.com'>DB-IP</a>, and <a href='https://www.ipdeny.com/'>IPdeny</a>).

Reflector count by sub-region:


| Sub-region | Reflector Count |
| :--------- | :-------------- |
| Northern America | 41915 |
| Western Europe | 37036 |
| Eastern Europe | 25544 |
| Eastern Asia | 15605 |
| Northern Europe | 10667 |
| Latin America and the Caribbean | 8248 |
| South-eastern Asia | 7730 |
| Southern Europe | 5733 |
| Sub-Saharan Africa | 3531 |
| Southern Asia | 3130 |
| Western Asia | 1914 |
| Australia and New Zealand | 1696 |
| Central Asia | 833 |
| Northern Africa | 148 |
| Melanesia | 14 |
| Polynesia | 12 |
| Micronesia | 7 |
| **Total** | **163763** |
