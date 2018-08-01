# influxdb-cluster

Proof-of-concept an influxdb cluster to accommodate scalability and high availability feature

                  |-------------|
HAProxy-LB-1 ---- | influx-1    |
                  | influx-2    |
HAProxy-LB-2 ---- | ...         |
                  | influx-n    |
                  |-------------|
