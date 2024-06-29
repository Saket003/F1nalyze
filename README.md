Code was run locally on CPU
Team Name: RIP Gary
Members: Saket Kandoi (saket03), Navneet Raj (navneetraj2)


'result_driver_standing' - Unique ID
'position' - Target Var

Converted numeric to floats

'date','dob' - Taking year and months; 'time_y' - to num.num float

Dropping (Less Relevant) -
- Date, time of fp1, fp2, fp3
Ignore for now - 'fp1_date', 'fp1_time', 'fp2_date', 'fp2_time', 'fp3_date', 'fp3_time'
- 'url' - Contest Name as Wiki URL, 'url_y', 'url_x', 

Dropping (Null) -
'quali_date' 'sprint_time' sprint_date' 'quali_time'
'positionText_y', - same as position data

Duplicates (Dropped for now, use for nulls) -
- 'number' - linked to driver
- 'rank' - related to points
- 'driver_code', 'forename', 'surname', 'driverRef', 'driver_num' - not needed
- 'company','constructorRef' - duplictae
- 'time_x' - duplicate to total time in ms
- 'status' - linked to statusID
- 'position_x', 'positionText_x', - similar to position order