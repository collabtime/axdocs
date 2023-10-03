### Event & Alarm Monitoring 

Monitoring system activities is critical to any security operation and within Access Expert we have several 
ways to monitor your system.

Two of the most commonly used tools that help manage system events, real-time situational awareness and 
workflow management are:
1. Event History – provides information on previously occurred events. This view is a moment in time 
view as the information only updates when the operator selects the ‘Refresh’ button. 
2. Live Monitoring – Provides information in real time. This view automatically updates as events and 
alarms occur.

Both types of windows open based upon a system wide view so monitoring all controllers, sites, sensors 
and devices. The windows can be modified by the operator to only show relevant information by adding, 
removing and resizing individual columns as well as exposing hidden information by using the “+” button as
seen in the People List window.

In the Event History, information is displayed based upon what you have selected for timeframe in the
upper right. Simple commands such as 1D (day) or 1h (hour) can be entered in the cell and the window will
automatically updated accordingly. Time based filtering includes (m) for minute, (h) for hour, (d) for day, 
(M) for Month and (y) for year. Operators can also search based upon specific date and time ranges by 
selecting ‘Date Range’ from the drop-down menu.

![Event History](/axdocs/assets/eventAndAlarmMonitoring1.png)

Additional filtering can be done by selecting the Priority Legend or by manually entering a specific Priority 
number. The priority numbers are assigned to events to indicate priority. When using the Priority filtering,
the system will only return results for events and alarms for that priority number and higher. The overall 
range is from 0 – 255. Additional Priority Color ranges can be configured also and will be addressed in the 
“Alarm Priority Default” section.

Information can further be searched by manually typing in specific information such as a name, or number.
In the example below, we are searching the most recent information. Criteria 1 is “Wednesday” and criteria 
2 is “Out”. The system will automatically present information highlighted in Yellow which matches both 
criteria. Additional items can be added by including a space between the items being searched for. It is 
important to note that the search feature here only searches the loaded events. Scroll to the bottom of the 
page to load more information.

![Event History](/axdocs/assets/eventAndAlarmMonitoring2.png)

Once a view is built, it can be saved and re-used later. To save a filtered view simply click “Grid Layout” then 
select “Save”. Once a name is applied to the Grid Layout it will automatically be saved for that operator. The 
operator can then click on “Grid Layout”, hover over “Load” and then select the previously saved Grid Layout to 
load it into the view. By clicking the “Manage” option, the user can remove un-used grid layouts.

If the operator wants to search for a specific Event Source instead 
of the full system, then clicking the ‘Filters’ option then selecting 
‘Event Sources’ will open a filtering window. This will open the 
Event Sources window where the operator can add sources by 
typing in the device name. Access Expert will automatically 
present the operator with relevant items. Once completed select 
OK and the system will re-filter the Event or Live windows for 
information only on those new sources.
