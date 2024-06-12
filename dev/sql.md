### Database optimization
##### Requests optimization
Avoid full table scan:
- avoid sorting
- avoid queries without `WHERE` conditions
- avoid functions or calculations on `WHERE` conditions (breaks indexes) 

Select only columns which is needed, do not use `SELECT *`

Profile queries with `EXPLAIN ANALYZE` and search for full table scans (marked as `Seq Scan`)


##### Table optimization
- Use optimal column types
- Add index to table `CREATE INDEX ON table`
- Use partitioning
- Perform `VACUUM` by schedule 


##### RDBMS engine optimization

- Tune database to not use spinning drive optimizations if it runs on SSD
- Play with isolation levels if it's okay to sacrifice redundancy

##### Horizontal scaling
Sharding using `citrus` or `pg_shardman`


