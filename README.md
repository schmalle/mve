#Speedcompare native MaxMind vs Elasticsearch

## Background

For DTAGs honeypot backend, we wanted to check, how native Maxmind API versus Elasticearch (both locally) perform.

**Requirements**

Maxmind GeoIP libraries at

    ("/var/lib/GeoIP/GeoIP.dat")
    ("/var/lib/GeoIP/GeoLiteCity.dat")
    ('/var/lib/GeoIP/GeoIPASNum.dat')
    
**Results**

Elapsed time for MaxMind: 0:07:25.186690

Elapsed time for ES: 0:01:00.066050

Total number of IPs: 64516