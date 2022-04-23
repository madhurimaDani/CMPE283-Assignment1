# CMPE283-Assignment 1
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
	•Logged into Google Cloud Platform with SJSU student account
	•Created a new project cmpe283 and set it as current project
	•In VM Instances tab, enabled Google Cloud Platform API
	•Opened cloud shell and executed the given command to spin up a VM
  
  <img width="1439" alt="-1" src="https://user-images.githubusercontent.com/37496654/164831597-992488d5-5123-4435-87b8-8eb15cd479cb.png">
  
        •Validated output of top command, df -h command and /proc/vmx to verify nested virtualization is enabled
  
  <img width="473" alt="-1 df command" src="https://user-images.githubusercontent.com/37496654/164836337-72133990-f121-4086-ba56-880deda27a11.png">

  <img width="1438" alt="-1 vmx proof" src="https://user-images.githubusercontent.com/37496654/164836362-aaa6b111-9262-41a6-8045-d4a328ced9d8.png">

  <img width="922" alt="-1 top command" src="https://user-images.githubusercontent.com/37496654/164836398-5c8204b5-29fe-492c-ab27-add56a14db52.png">

        •Created a new repository in git account for CMPE 283 assignments
        •Uploaded makefile and cmpe283-1.c file into git repository
	
<img width="1000" alt="1" src="https://user-images.githubusercontent.com/37496654/164836650-c99d3e1f-6329-4cf7-8fa2-f0c0403d83d4.png">

	•From VM, executed git clone command and download the files on VM. Forked and cloned linux repository
	
<img width="820" alt="2" src="https://user-images.githubusercontent.com/37496654/164836785-f436ede3-06b1-411c-8e4d-225f14abbed0.png">
	
	•Modified cmpe283-1.c file to read and display VMX configuration for process based, secondary process based, entry and exit MSRs
<img width="1143" alt="4" src="https://user-images.githubusercontent.com/37496654/164836910-0213effe-ba6a-4762-b532-a81d7b18ae3a.png">
	
	•Executed make command
<img width="955" alt="5" src="https://user-images.githubusercontent.com/37496654/164836990-3a719c43-19f5-4aad-aaa5-f651cf9b8ceb.png">

	•It failed, had to add below line into .c file
<img width="864" alt="3" src="https://user-images.githubusercontent.com/37496654/164837175-beb00107-b150-49f0-99d7-df842a2ca024.png">

	•Executed dmesg command to display all the logs and verify that the VMX capabilities for MSRs are displayed.
	
<img width="1168" alt="6" src="https://user-images.githubusercontent.com/37496654/164837426-60dc3e9b-4aad-48e3-8b56-68e92a14380b.png">
<img width="816" alt="7" src="https://user-images.githubusercontent.com/37496654/164837508-4a14dcc3-4be2-4282-814e-f4f9b95db089.png">

	•Committed and pushed final files into git repository
  

  
