## NYC Taxi Trip Data

FOIA/FOILed Taxi Trip Data from the NYC Taxi and Limousine Commission 2013. Released by http://chriswhong.com/open-data/foil_nyc_taxi/ trip_data.7z and trip_fare.7z are more efficiently compressed versions of the data, you probably want these files. The data is in csv format. 

- Id: `3`
- Homepage: [https://archive.org/details/nycTaxiTripData2013](https://archive.org/details/nycTaxiTripData2013)
- Versions: 1.0.0
- Size: 7.7G
- Format: CSV
- DownLoad: [https://dl.cnosdb.com/sample/nyc_taxi_trip_data.csv](https://dl.cnosdb.com/sample/nyc_taxi_trip_data.csv)
- Last Update: 2014-06-18

### Field Descriptions

| Colume             | Type            | Tag | Original        |
| -----------------  | ----------------| --- | --------------- |
| medallion          | BIGINT UNSIGNED | NO  |                 |
| hack_license       | BIGINT UNSIGNED | NO  |                 |
| vendor_id          | STRING          | YES |                 |
| rate_code          | BIGINT          | YES |                 |
| store_and_fwd_flag | STRING          | NO  |                 |
| pickup_datetime    | TIMESTAMP       | NO  | pickup_datetime |
| dropoff_datetime   | TIMESTAMP       | NO  |                 |
| passenger_count    | BIGINT          | NO  |                 |
| trip_time_in_secs  | BIGINT          | NO  |                 |
| trip_distance      | DOUBLE          | NO  |                 |
| pickup_longitude   | DOUBLE          | NO  |                 |
| pickup_latitude    | DOUBLE          | NO  |                 |
| dropoff_longtitude | DOUBLE          | NO  |                 |
| dropoff_latitude   | DOUBLE          | NO  |                 |

<details>
  <summary>Click here to show/hide data</summary>

  | medallion | hack_license | vendor_id | rate_code | store_and_fwd_flag | pickup_datetime | dropoff_datetime | passenger_count | trip_time_in_secs | trip_distance | pickup_longitude | pickup_latitude |dropoff_longtitude | dropoff_latitude |
  | -------------                    | --------------                   | --  | - | - | ------------------- | ------------------- | - | --- | ---- | ---------- | --------- | ---------- | --------- |
  | 89D227B655E5C82AECF13C3F540D4CF4 | BA96DE419E711691B9445D6A6307C170 | CMT | 1 | N | 2013-01-01 15:11:48 | 2013-01-01 15:18:10 | 4 | 382 | 1.00 | -73.978165 | 40.757977 | -73.989838 | 40.751171 |
  |               |                  |                                  |     |   |   |                     |                     |   |     |      |            |           |            |           |
</details>

