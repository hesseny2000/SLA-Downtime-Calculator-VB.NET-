# SLA-Downtime-Calculator-VB.NET-
Calculate Enterprise downtime based on  ISP SLA
Features Covered

Input:
Start Date/Time
End Date/Time
Options:
 Include all time
 Working hours only (8 AM → 4 PM)
 Exclude weekends (Friday & Saturday)

Output:
Total downtime (Hours / Minutes)

Logic Explanation ::: 
1. Weekend Handling : **If current.DayOfWeek = DayOfWeek.Friday Or current.DayOfWeek = DayOfWeek.Saturday**
2. Working Hours Window :: ***8:00 AM → 4:00 PM***
3. Smart Time Adjustment :
     If time before 8 → move to 8
     If after 4 → jump to next day
    Always calculate valid overlap only

   
