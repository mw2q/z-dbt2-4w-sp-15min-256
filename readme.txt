Sun May 10 20:51:36 BST 2015

Linux ECSPGSQL 3.0.76-0.11-default #1 SMP Fri Jun 14 08:21:43 UTC 2013 (ccab990) s390x s390x s390x GNU/Linux
Command line: /home/mark/bin/dbt2-run-workload -a pgsql -c 40 -d 900 -w 4 -o z-dbt2-4w-sp-15min -s 100 -n -p -c max_connections=60 -c checkpoint_segments=180 -c checkpoint_timeout=30min -c shared_buffers=2GB -c work_mem=64MB -c effective_cache_size=4GB -c autovacuum=off
RDBMS: pgsql
Database Name: dbt2
Database Scale Factor: 4 warehouses
Test Duration: 900 seconds
Database Connections: 40
