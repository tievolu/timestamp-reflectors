# timestamp-reflectors
A list of IP addresses that respond to ICMP type 13 (timestamp) requests, in CSV format.

According to <a href='https://datatracker.ietf.org/doc/html/rfc792'>RFC 792</a> (page 17), timestamps in ICMP type 13 messages should describe the number of milliseconds since midnight UTC, but some reflectors don't follow this requirement. Some reflectors respond with random nonsensical values - these reflectors are not included in the lists. Other reflectors return usable timestamps, but they are significantly offset from number-of-milliseconds-since-midnight-UTC by a consistent amount. Each reflector's offset is included in the lists.

The subdirectories contain CSV files organised by country, region, and sub-region (<a href='https://db-ip.com'>IP Geolocation by DB-IP</a>).

Reflector count by sub-region:


| Sub-region | Reflector Count |
| :--------- | :-------------- |
| Northern America | 40188 |
| Western Europe | 32731 |
| Eastern Europe | 22396 |
| Eastern Asia | 15292 |
| Northern Europe | 11689 |
| South-eastern Asia | 5335 |
| Southern Europe | 4744 |
| Latin America and the Caribbean | 3324 |
| Southern Asia | 2650 |
| Australia and New Zealand | 1578 |
| Sub-Saharan Africa | 1467 |
| Western Asia | 1179 |
| Central Asia | 540 |
| Northern Africa | 73 |
| Polynesia | 6 |
| Micronesia | 3 |
| Melanesia | 3 |
| **Total** | **143198** |
