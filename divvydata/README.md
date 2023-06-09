## Divvy Data

Historical trip data available to the public

Here you'll find Divvy's trip data for public use. So whether you're a policy maker, transportation professional, web developer, designer, or just plain curious, feel free to download it, map it, animate it, or bring it to life!

Note: This data is provided according to the Divvy Data License Agreement and released on a monthly schedule.

- Id: `2`
- Homepage: [https://divvybikes.com/system-data](https://divvybikes.com/system-data)
- Versions: csv
- Size: 15.4 MB
- Format: CSV
- DownLoad: [https://divvy-tripdata.s3.amazonaws.com/index.html](https://divvy-tripdata.s3.amazonaws.com/202304-divvy-tripdata.zip)
- License: [https://dl.cnosdb.com/sample/divvy_tripdata.csv](https://dl.cnosdb.com/sample/divvy_tripdata.csv)
- Last Update: 2023-05-05

### Field Descriptions

| Colume               | Type      | Tag | Original   |
| -----------          | --------- | --- | --------   |
| ride_id              | BIGINT    | NO  | 
| rideable_type        | STRING    | NO  |            |
| time                 | TIMESTAMP | NO  | started_at |
| ended_at             | TIMESTAMP | NO  |            |
| start_station_name   | STRING    | NO  |            |
| start_station_id     | BIGINT    | YES |            |
| end_station_name     | STRING    | NO  |            |
| end_station_id       | BIGINT    | NO  |            |
| start_lat            | DOUBLE    | NO  |            |
| start_lng            | DOUBLE    | NO  |            |
| end_lat              | DOUBLE    | NO  |            |
| end_lng              | DOUBLE    | NO  |            |
| member_casual        | STRING    | YES |            |


<details>
  <summary>Click here to show/hide data</summary>

  | ride_id | rideable_type | started_at | ended_at | start_station_name | start_station_id | end_station_name | end_station_id | start_lat | start_lng | end_lat | end_lng | member_casual |
  | --------| --------------| -----------| -------- | ------------------ | ---------------- | --------------   | --------       | --------  |  -------  | ------- | ------------- |--------|
  | 02668AD35674B983 | docked_bike | 2020/5/27 10:03:52 | 2020/5/27 10:16:49 | Franklin St & Jackson Blvd | 36 | Wabash Ave & Grand Ave | 199 | 41.8777 |  -87.6353 |  41.8915 |  -87.6268 |member| 
  |         |        |             |                    |                    |                            |    |                        |     |         |           |          |           |
</details>