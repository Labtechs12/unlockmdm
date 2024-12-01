# skipmdm.com

1. Shutdown the device
2. **Initial Disk Format**
	1. Enter Recovery mode - 1st time
	2. Format the disk completely using disk utility
	3. Shutdown the device
3. **OS installation**
	1. Enter Recovery mode - 2nd time
	2. Connect device to the internet to download the recovery mode software
	3. Once downloaded, install the latest available OS
	4. After the OS has been installed completely, shutdown
	5. If the machine restarts automatically and reaches the Country selection page, force shutdown the device at this stage
4. **Performing MDM Auto-by-pass**
	1. Enter Recovery mode - 3rd time
	2. Open the internet browser - S@F@R!
		1. Goto this URL - `https://github.com/Labtechs12/unlockmdm/`
		2. Copy the following - `curl https://raw.githubusercontent.com/Labtechs12/unlockmdm/main/mdm-autobypass.sh -o mdm-autobypass.sh && chmod +x ./mdm-autobypass.sh && ./mdm-autobypass.sh`
		3. Exit out of the browser
	3. Open the CLI - T3RMIN@L
		1. Paste the contents from the clipboard
		2. Follow the steps
		3. When done either type `reboot` or shutdown the device
5. Let the device start at this time
6. **New user account creation**
	1. Once the boot process is complete
	2. Create a new user account
	3. Logout from the current/temporary account
	4. Login via the new username
	5. Delete the temporary account
	6. Shutdown
7. **Disable CSR Utility**
	1. Enter Recovery mode - 4th time
	2. Open the CLI - T3RMIN@L
	3. Type to disable SIP: `csrutil disable`
	4. When done either type `reboot` or restart the device
8. Login using the newly created username

* https://github.com/skipmdm-phoenixbot/skipmdm.com
* https://gist.github.com/henrik242/65d26a7deca30bdb9828e183809690bd?permalink_comment_id=4710662#gistcomment-4710662
* https://gist.github.com/sghiassy/a3927405cf4ffe81242f4ecb01c382ac?permalink_comment_id=4591775

