# CMPE283-Assignment1
## Assignment 1: Discovering VMX Features

### Team Members
	•	Madhurima Subodh Dani (015261974)
	•	Shreemathi Duvvuri (015273102)

### [1] For each member in your team, provide 1 paragraph detailing what parts of the lab that member implemented / researched.
- Madhurima
  - Discussed steps to be performed for assignment 1
  - Installed required kernel modules in the VM
  - Modified cmpe283-1.c file 
  - Collected output of the assignment  
  - Pushed code to git repo
- Shreemathi
  - Watched relevant videos from canvas and gathered understanding on how to proceed and what to do
  - Discussed steps to be performed for assignment 1
  - Researched about configuring the vmware hypervisor
  - Set up Google Cloud Platform Account and configured VM in Google Cloud Platform
  - Updated git files and README.md

### [2] Steps Followed
	•	Logged into Google Cloud Platform with SJSU student account
	•	Created a new project cmpe283 and set it as current project
	•	In VM Instances tab, enabled Google Cloud Platform API
	•	Opened cloud shell and executed the given command to spin up a VM
  
  <img width="1439" alt="-1" src="https://user-images.githubusercontent.com/37496654/164831597-992488d5-5123-4435-87b8-8eb15cd479cb.png">
  
  •	Validated output of top command, df -h command and /proc/vmx
  
  <img width="473" alt="-1 df command" src="https://user-images.githubusercontent.com/37496654/164836337-72133990-f121-4086-ba56-880deda27a11.png">

  <img width="1438" alt="-1 vmx proof" src="https://user-images.githubusercontent.com/37496654/164836362-aaa6b111-9262-41a6-8045-d4a328ced9d8.png">

  <img width="922" alt="-1 top command" src="https://user-images.githubusercontent.com/37496654/164836398-5c8204b5-29fe-492c-ab27-add56a14db52.png">


  •	Created a new repository in git account for CMPE 283 assignments
	•	Uploaded makefile and cmpe283-1.c file into git repository
	•	From VM, executed git clone command and download the files on VM
	•	Modified cmpe283-1.c file to fetch required details
	•	Executed make command
	•	It failed, had to add below line into .c file
	•	Executed dmesg command
	•	Pushed final files into git
  

  
