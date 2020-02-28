# Windows Scheduler : For Auto Execution of EXE files

Need to execute a specific program on a daily basis for a specific time. 
basis by using BAT file.

Steps to run BAT using Windows Scheduler.

a) Navigate to Start >> Control Panel >> Administrative Tools >> Task Scheduler
b) Click on Task Scheduler >> Create Task option

c) ‘Create Task’ UI will open.  In General Tab, Enter the Task Name.

d) In case you want the scheduler to run in case the user is logged off, then select the checkbox (Run whether the user is logged on or not).
e) Then navigate to Action tab and select New.
f) You will see the ‘New Action’ UI.


g) In ‘Program/Script’, select BOT BAT file, for which you want to execute using the Browse button.
h) In ‘Add arguments (optional)’ field User Id, Password, and Company Name.  Separate these fields by comma (ADMIN,ADMIN,SAMINC)
i) Click on OK >> ‘New Action’ UI will get closed.
j) Now, navigate to Triggers Tab >> New >> ‘New Trigger’; an UI will get opened.
k) Add a scheduler to run the EXE.

l) Click on OK >> New Trigger UI will get closed.
m) Now click on OK button in ‘Create Task’ UI.
n) A pop up will get opened asking for System User Id and Password. Enter details and click on OK.(Optional popup)

This way, the BOT file will run on a daily basis as set in windows scheduler.
