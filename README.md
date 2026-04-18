# timestamp-reflectors
A list of IP addresses that respond to ICMP type 13 (timestamp) requests, in CSV format.

According to <a href='https://datatracker.ietf.org/doc/html/rfc792'>RFC 792</a> (page 17), timestamps in ICMP type 13 messages should describe the number of milliseconds since midnight UTC, but some reflectors don't follow this requirement. Some reflectors respond with random nonsensical values - these reflectors are not included in the lists. Other reflectors return usable timestamps, but they are significantly offset from number-of-milliseconds-since-midnight-UTC by a consistent amount. Each reflector's offset is included in the lists.

The subdirectories contain CSV files organised by location, with the granularity and accuracy depending on what data was available from <a href='https://dev.maxmind.com/geoip/geolite2-free-geolocation-data/'>Maxmind</a>, <a href='https://db-ip.com'>DB-IP</a>, and <a href='https://www.ipdeny.com/'>IPdeny</a>).

Reflector count by sub-region:


| Sub-region | Reflector Count |
| :--------- | :-------------- |
| Northern America | 43116 |
| Western Europe | 37415 |
| Eastern Europe | 27119 |
| Eastern Asia | 16119 |
| Northern Europe | 10823 |
| Latin America and the Caribbean | 8334 |
| South-eastern Asia | 8035 |
| Southern Europe | 5812 |
| Sub-Saharan Africa | 3782 |
| Southern Asia | 3301 |
| Western Asia | 1959 |
| Australia and New Zealand | 1839 |
| Central Asia | 899 |
| Northern Africa | 148 |
| Melanesia | 14 |
| Polynesia | 12 |
| Micronesia | 7 |
| **Total** | **168734** |
