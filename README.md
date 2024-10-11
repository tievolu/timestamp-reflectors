# timestamp-reflectors
A list of IP addresses that respond to ICMP type 13 (timestamp) requests, in CSV format.

According to <a href='https://datatracker.ietf.org/doc/html/rfc792'>RFC 792</a> (page 17), timestamps in ICMP type 13 messages should describe the number of milliseconds since midnight UTC, but some reflectors don't follow this requirement. Some reflectors respond with random nonsensical values - these reflectors are not included in the lists. Other reflectors return usable timestamps, but they are significantly offset from number-of-milliseconds-since-midnight-UTC by a consistent amount. Each reflector's offset is included in the lists.

The subdirectories contain CSV files organised by country, region, and sub-region (<a href='https://db-ip.com'>IP Geolocation by DB-IP</a>).

Reflector count by sub-region:


| Sub-region | Reflector Count |
| :--------- | :-------------- |
| Western Europe | 26433 |
| Northern America | 24885 |
| Eastern Europe | 21749 |
| Eastern Asia | 13358 |
| Northern Europe | 11428 |
| South-eastern Asia | 5205 |
| Southern Europe | 4628 |
| Southern Asia | 2632 |
| Latin America and the Caribbean | 2567 |
| Australia and New Zealand | 1571 |
| Sub-Saharan Africa | 1184 |
| Western Asia | 1122 |
| Central Asia | 540 |
| Northern Africa | 69 |
| Polynesia | 6 |
| Melanesia | 3 |
| Micronesia | 3 |
| Unknown | 25815 |
| **Total** | **143198** |
