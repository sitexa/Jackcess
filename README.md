# Jackcess
Access to MySQL scripts

#  Import data into mysql

mysql>set autocommit=0;source insert_Sites.sql;commit;

mysql>set autocommit=0;source insert_Posts_batch.sql;commit;
