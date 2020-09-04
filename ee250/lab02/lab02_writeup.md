4.1 
	git clone git@github.com:my-name/my-imaginary-repo.git
	cd my-imaginary-repo
	touch my_second_file.py
	git add "my_second_file.py"
	git commit -m "Second File"
	git push

4.2
	I developed all my code on the Vm and then pushed to Github. Then pulled to the RPi. There were some
	times where I was modifying the code on the RPi, however, I would constantly forget to push and pull between devices,
	frequently causing splits in my repos, like a different version would be on the RPi and a different version on Github
	and then another different version would also be on the VM and I haven't figured out yet how to merge these repos.
	Also, everytime I pushed from my VM to Github, it would always ask for my Github username and password, so I have to look at
	how to fix that issue.

	For next lab, I would like to get better at learning different Git commands and maybe limit all my editing to the RPi.

4.3
	The delay time is 60 ms as encoded by the function in grovepi.py. In communicating between the Atmega328P, the RPi seems to use USB protocol
	to allow the Atmega to read the data from the Ultrasonic Ranger.  