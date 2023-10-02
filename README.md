# Parts and Packaging Automated Approval 
Data pertaining to parts and packaging information is automatically analyzed and approved using Python and Selenium. Built by Jason Peters
## Problem
Transportation Management System (TMS) uses parts and packaging information to inform decisions regarding truckload planning. Parts and packaging information is presented in rows that contain dimensions, packaging IDs, max quantities, and secondary pallet information. The information must be reviewed for errors and submitted one row at a time. This is an incredibly simple task and an ineffective use of company time.
## Solution
I used Google, StackOverflow, and ChatGPT to build a Python/Selenium code that automates this task. Selenium is capable of web page interaction such as reading and clicking while Python acts as a decision maker. Together, they perform the task without tiring and without human error. I also turned this into an executable file so others at my company can use it.
## Description
![image](https://github.com/jasonpetersops/approvaldestroyer/assets/146475554/fedc5c75-38d7-42aa-a93b-07b09a8beea9)
<br>
This is the parts and packaging approval dashboard. The data values should not be abnormally high and the data values should not be blank. If the option for a secondary pallet is switched on, then the secondary pallet ID should contain the identifier SPLT. Lastly, only data that has been requested by SidhdeeBhase should be approved. If any of these components are unacceptable, then the row should be skipped for later review.
