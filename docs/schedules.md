### Schedules
Schedules are used in Access Expert to determine days of the week and times of days that functions or events 
will occur. Each Schedule can have a single, or up to 12, time intervals associated with it. Sets of time intervals
make up a Schedule which can be used throughout the system (i.e. Access Levels, Scheduled Unlocks,
customized logic functions).

The 24X7, “Always”, schedule is a default schedule and cannot be modified. Although the schedule shows with 
no intervals, it is always active. A secondary 24x7, “Always” schedule cannot be added via the UI. It is best 
practice to use the Always Schedule that comes by default with your instance when needed a schedule that is 
never inactive.

Within a Schedule, a Holiday exception can be added which will tell the system to ignore the Holiday intervals
on those specific days. Holidays are a full day duration and not intended to be partial days or specific times of a 
day.

To Add a Schedule
1. Select the ‘Access Configuration’ Tab.
2. Select “Schedules”.
3. Click the “Add 
Schedule” button.
4. Enter a Display 
Name for the 
schedule.
5. Click “Add Schedule 
Duration”.
6. Mark days active as 
required.
7. Enter Start/End Times.
8. (OPTIONAL) Apply Holiday Exception set.
9. Click “Save” or “Save & Close”.

Additionally, Schedules can be used based upon a One-Off Date. A One-Off Date is a single occurrence of a 
Schedule unique to a specific day of the Month and is selected using the Calendar menu that appears when the 
drop-down button is selected. Only (1) One Off Date can exist in a single Schedule. For multiple-day alternate 
scheduling, see Special Dates.

When using One Off Dates, the date 
selected in the calendar needs to 
match the day of the week in the 
schedule interval. As an example, if 
October 31st happens to be on a 
Tuesday then Tuesday should also be selected in the interval.

Schedule intervals must have a start and end time that are different for the schedule to have an active time. If 
the interval starts at 12:00 AM and ends at 12:00 AM, there is no time difference and therefore no time 
covered. A (+1) by the end time indicates that the interval selected spans midnight.
