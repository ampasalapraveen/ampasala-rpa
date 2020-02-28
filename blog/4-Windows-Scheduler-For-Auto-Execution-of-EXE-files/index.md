# Windows Scheduler for Auto Execution of EXE files

Execute a specific program on a daily basis on a specific time by using BAT file.

## Steps to run BAT using Windows Scheduler.

1. Navigate to Start >> Control Panel >> Administrative Tools >> Task Scheduler

2. Click on Task Scheduler >> Create Task option

![First](https://ampasalapraveen.github.io/ampasala-rpa/blog/4-Windows-Scheduler-For-Auto-Execution-of-EXE-files/1.jpeg)

3. ‘Create Task’ UI will open.  In General Tab, Enter the Task Name.

![Second](https://ampasalapraveen.github.io/ampasala-rpa/blog/4-Windows-Scheduler-For-Auto-Execution-of-EXE-files/2.jpeg)

4. In case you want the scheduler to run in case the user is logged off, then select the checkbox (Run whether the user is logged on or not).

5. Then navigate to Action tab and select New.

6. You will see the ‘New Action’ UI.

![Third](https://ampasalapraveen.github.io/ampasala-rpa/blog/4-Windows-Scheduler-For-Auto-Execution-of-EXE-files/3.jpeg)

7. In ‘Program/Script’, select BOT BAT file, for which you want to execute using the Browse button.

8. In ‘Add arguments (optional)’ field User Id, Password, and Company Name.  Separate these fields by comma (ADMIN,ADMIN,SAMINC)

9. Click on OK >> ‘New Action’ UI will get closed.

10. Now, navigate to Triggers Tab >> New >> ‘New Trigger’; an UI will get opened.

11. Add a scheduler to run the EXE.


![Fourth](https://ampasalapraveen.github.io/ampasala-rpa/blog/4-Windows-Scheduler-For-Auto-Execution-of-EXE-files/4.jpeg)


12. Click on OK >> New Trigger UI will get closed.

13. Now click on OK button in ‘Create Task’ UI.

14. A pop up will get opened asking for System User Id and Password. Enter details and click on OK.(Optional popup)

This way, the BOT file will run on a daily basis as set in windows scheduler.
