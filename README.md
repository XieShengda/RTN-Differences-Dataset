# WHU BDS-3 ultra-rapid and final orbits (2020/04/09 to 2023/01/03)
The dataset provided is formatted in a comma-separated values (CSV) file, readily accessible using common data analysis tools such as Pandas. Detailed information regarding the dataset's structure and contents is as follows: 

| Field Name     | Data Type | Comment            |
| :------------- | :-------- | :--------------------------- |
| prn            | INTEGER   | PRN of satellites.                  |
| sat_sys        | TEXT      | Satellite systems, such as BDS.                 |
| year           | INTEGER   | Year.                        |
| doy            | INTEGER   | Day of year.                 |
| month          | INTEGER   | Month.                       |
| day            | INTEGER   | Day.                         |
| hour           | INTEGER   | Hour.                        |
| min            | INTEGER   | Minute.                      |
| sec            | REAL      | Second.                      |
| ux             | REAL      | X-axis coordinates in kilometers (km) of the ultra-rapid orbits in ECEF frame.                  |
| uy             | REAL      | Y-axis coordinates in kilometers (km) of the ultra-rapid orbits in ECEF frame.                 |
| uz             | REAL      | Z-axis coordinates in kilometers (km) of the ultra-rapid orbits in ECEF frame.                   |
| fx             | REAL      | X-axis coordinates in kilometers (km) of the final orbits in ECEF frame.           |
| fy             | REAL      | Y-axis coordinates in kilometers (km) of the final orbits in ECEF frame.                |
| fz             | REAL      | Z-axis coordinates in kilometers (km) of the final orbits in ECEF frame.                  |
| eci_ux         | REAL      | X-axis coordinates in meters (m) of the ultra-rapid orbits in ECI frame.                 |
| eci_uy         | REAL      |Y-axis coordinates in meters (m) of the ultra-rapid orbits in ECI frame.                 |
| eci_uz         | REAL      | Z-axis coordinates in meters (m) of the ultra-rapid orbits in ECI frame.              |
| eci_fx         | REAL      |X-axis coordinates in meters (m) of the final orbits in ECI frame.             |
| eci_fy         | REAL      |Y-axis coordinates in meters (m) of the final orbits in ECI frame.           |
| eci_fz         | REAL      | Z-axis coordinates in meters (m) of the final orbits in ECI frame.        |
| eci_uxv        | REAL      | Velocities in meters per second (m/s) in the x-axis of ultra-rapid orbits in the ECI frame.     |
| eci_uyv        | REAL      | Velocities in meters per second (m/s) in the y-axis of ultra-rapid orbits in the ECI frame.    |
| eci_uzv        | REAL      |Velocities in meters per second (m/s) in the z-axis of ultra-rapid orbits in the ECI frame.    |
| radial         | REAL      | Orbit differences in centimeters (cm) in the tangential direction.                  |
| tangential     | REAL      | Orbit differences in centimeters (cm) in the along-track direction.               |
| normal         | REAL      | Orbit differences in centimeters (cm) in the cross-track direction.                 |
