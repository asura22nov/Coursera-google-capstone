# Coursera-google-capstone
# Coursera Google Data Analytics Course Capstone Data Analysis case study - Cyclistic bike-share analysis case study!

# Summary :
# The TXT file includes the SQL steps used for Cyclistic bike-share analysis case study for the CAPTSTONE.

# #File Sources:
1. https://divvy-tripdata.s3.amazonaws.com/202004-divvy-tripdata.zip
2. https://divvy-tripdata.s3.amazonaws.com/202005-divvy-tripdata.zip
3. https://divvy-tripdata.s3.amazonaws.com/202006-divvy-tripdata.zip
4. https://divvy-tripdata.s3.amazonaws.com/202007-divvy-tripdata.zip
5. https://divvy-tripdata.s3.amazonaws.com/202008-divvy-tripdata.zip
6. https://divvy-tripdata.s3.amazonaws.com/202009-divvy-tripdata.zip
7. https://divvy-tripdata.s3.amazonaws.com/202010-divvy-tripdata.zip
8. https://divvy-tripdata.s3.amazonaws.com/202011-divvy-tripdata.zip
9. https://divvy-tripdata.s3.amazonaws.com/202012-divvy-tripdata.zip
10. https://divvy-tripdata.s3.amazonaws.com/202101-divvy-tripdata.zip
11. https://divvy-tripdata.s3.amazonaws.com/202102-divvy-tripdata.zip
12. https://divvy-tripdata.s3.amazonaws.com/202103-divvy-tripdata.zip
13. https://divvy-tripdata.s3.amazonaws.com/202104-divvy-tripdata.zip
14. https://divvy-tripdata.s3.amazonaws.com/202105-divvy-tripdata.zip
15. https://divvy-tripdata.s3.amazonaws.com/202106-divvy-tripdata.zip
16. https://divvy-tripdata.s3.amazonaws.com/Divvy_Stations_Trips_2013.zip
17. https://divvy-tripdata.s3.amazonaws.com/Divvy_Stations_Trips_2014_Q1Q2.zip
18. https://divvy-tripdata.s3.amazonaws.com/Divvy_Stations_Trips_2014_Q3Q4.zip
19. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2015-Q1Q2.zip
20. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2015_Q3Q4.zip
21. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2016_Q1Q2.zip
22. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2016_Q3Q4.zip
23. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2017_Q1Q2.zip
24. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2017_Q3Q4.zip
25. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2018_Q1.zip
26. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2018_Q2.zip
27. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2018_Q3.zip
28. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2018_Q4.zip
29. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q1.zip
30. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q2.zip
31. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q3.zip
32. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2019_Q4.zip
33. https://divvy-tripdata.s3.amazonaws.com/Divvy_Trips_2020_Q1.zip
34. https://divvy-tripdata.s3.amazonaws.com/index.html


# Files Considered:
# Last 12 Months

202007-divvy-tripdata.csv
202008-divvy-tripdata.csv
202009-divvy-tripdata.csv
202010-divvy-tripdata.csv
202011-divvy-tripdata.csv
202012-divvy-tripdata.csv
202101-divvy-tripdata.csv
202102-divvy-tripdata.csv
202103-divvy-tripdata.csv
202104-divvy-tripdata.csv
202105-divvy-tripdata.csv
202106-divvy-tripdata.csv


# Data Cleaning:
1. Renamed files to suit SQL TABLE Creation
2. Trail and error in choosing the column data types. (Finally stick with varchar))


#SQL Command

#Drop tables command to tables created

drop table divvy_tripdata_202007;
drop table divvy_tripdata_202008;
drop table divvy_tripdata_202009;
drop table divvy_tripdata_202010;
drop table divvy_tripdata_202011;
drop table divvy_tripdata_202012;
drop table divvy_tripdata_202101;
drop table divvy_tripdata_202102;
drop table divvy_tripdata_202103;
drop table divvy_tripdata_202104;
drop table divvy_tripdata_202105;
drop table divvy_tripdata_202106;


 #Created individual files for the tables
 
CREATE TABLE divvy_tripdata_202007
(
ride_id varchar(25)         ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202008
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);


CREATE TABLE divvy_tripdata_202009
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202010
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202011
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202012
(
ride_id varchar(25)         ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202101
(
ride_id varchar(25)         ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202102
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202103
(
ride_id varchar(25)         ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202104
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202105
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);

CREATE TABLE divvy_tripdata_202106
(
ride_id varchar(25)        ,
rideable_type varchar(25) ,
started_at  datetime    ,
ended_at  datetime    ,
start_station_name varchar(65) ,
start_station_id varchar(65)         ,
end_station_name varchar(65) ,
end_station_id varchar(65)         ,
start_lat  varchar(65),
start_lng  varchar(65),
end_lat varchar(65),
end_lng varchar(65),
member_casual varchar(25) 
);
#--//
#========
#-- ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual
#

 #loading Data into the SQL
 
 
LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202007.csv" 
INTO TABLE divvy_tripdata_202007 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
;

LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202008.csv" 
INTO TABLE divvy_tripdata_202008 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
; 
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202009.csv" 
INTO TABLE divvy_tripdata_202009 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202010.csv" 
INTO TABLE divvy_tripdata_202010 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202011.csv" 
INTO TABLE divvy_tripdata_202011 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202012.csv" 
INTO TABLE divvy_tripdata_202012 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202101.csv" 
INTO TABLE divvy_tripdata_202101 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202102.csv" 
INTO TABLE divvy_tripdata_202102 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202103.csv" 
INTO TABLE divvy_tripdata_202103 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202104.csv" 
INTO TABLE divvy_tripdata_202104 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202105.csv" 
INTO TABLE divvy_tripdata_202105 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 LOAD DATA INFILE "C:\\ProgramData\\MySQL\\MySQL Server 8.0\\Uploads\\divvy_tripdata_202106.csv" 
INTO TABLE divvy_tripdata_202106 
FIELDS TERMINATED BY ',' 
LINES TERMINATED BY '\n' 
IGNORE 1 LINES 
(ride_id,rideable_type,started_at,ended_at,start_station_name,start_station_id,end_station_name,end_station_id,start_lat,start_lng,end_lat,end_lng,member_casual)
 ;
 
 
 --Create View to merage files into 1 year files
 
CREATE VIEW divvy_tripdata_last_12m
AS
(
select * FROM divvy_tripdata_202007
UNION ALL
select * FROM divvy_tripdata_202008
UNION ALL
select * FROM divvy_tripdata_202009
UNION ALL
select * FROM divvy_tripdata_202010
UNION ALL
select * FROM divvy_tripdata_202011
UNION ALL
select * FROM divvy_tripdata_202012
UNION ALL
select * FROM divvy_tripdata_202101
UNION ALL
select * FROM divvy_tripdata_202102
UNION ALL
select * FROM divvy_tripdata_202103
UNION ALL
select * FROM divvy_tripdata_202104
UNION ALL
select * FROM divvy_tripdata_202105
UNION ALL
select * FROM divvy_tripdata_202106
);

# Create View to Flow steps as per the guide


CREATE VIEW divvy_tripdata_last_12m_ride_week AS
(
Select
a.*
,TIMEDIFF(a.ended_at , a.started_at) AS ride_length
,DATE_FORMAT(a.started_at, "%w") AS day_of_week 
FROM 
divvy_tripdata_last_12m As a
);

--Analysis

select 
AVG(ride_length)
,max(ride_length)
from 
divvy_tripdata_last_12m_ride_week;


select
day_of_week,
count(*)
from 
divvy_tripdata_last_12m_ride_week
GROUP BY
day_of_week
ORDER BY
day_of_week;

