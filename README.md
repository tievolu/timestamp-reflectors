# timestamp-reflectors
A list of IP addresses that respond to ICMP type 13 (timestamp) requests, in CSV format.

According to <a href='https://datatracker.ietf.org/doc/html/rfc792'>RFC 792</a> (page 17), timestamps in ICMP type 13 messages should describe the number of milliseconds since midnight UTC, but some reflectors don't follow this requirement. Some reflectors respond with random nonsensical values - these reflectors are not included in the lists. Other reflectors return usable timestamps, but they are significantly offset from number-of-milliseconds-since-midnight-UTC by a consistent amount. Each reflector's offset is included in the lists.

The subdirectories contain CSV files organised by location, with the granularity and accuracy depending on what data was available from <a href='https://dev.maxmind.com/geoip/geolite2-free-geolocation-data/'>Maxmind</a>, <a href='https://db-ip.com'>DB-IP</a>, and <a href='https://www.ipdeny.com/'>IPdeny</a>).

Reflector count by sub-region:


| Sub-region | Reflector Count |
| :--------- | :-------------- |
| Northern America | 42092 |
| Western Europe | 31432 |
| Eastern Europe | 22174 |
| Eastern Asia | 13784 |
| Northern Europe | 13007 |
| South-eastern Asia | 5284 |
| Southern Europe | 4636 |
| Latin America and the Caribbean | 3059 |
| Southern Asia | 2600 |
| Sub-Saharan Africa | 1765 |
| Australia and New Zealand | 1583 |
| Western Asia | 1172 |
| Central Asia | 532 |
| Northern Africa | 66 |
| Polynesia | 6 |
| Micronesia | 3 |
| Melanesia | 3 |
| **Total** | **143198** |
