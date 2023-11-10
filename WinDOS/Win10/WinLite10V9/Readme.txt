Windows 10 will run fast on old computers after this cleanup.

	When you remove MS Edge there will be IE11!
	You must hide Search from TaskBar if you remove MS Cortana because it is without function.
	You can use search in File Explorer as normal.
	Following Apps are installed on Server 2016: Calculator and Store.

Here are the steps:

Important!!! Disconnect from Internet because setup will run updates immediately!

1. Put this folder with files on your Windows 10 Setup USB/Disc (or anywhere else you can access during early windows setup; caution you have no explorer only command prompt during setup!).

2. Do a clean installation, reset or update of Windows 10 and wait
   until the Windows Setup ask you for input (title at this setup step: ‘Get going fast’) but enter nothing for now!!!

3. Now press Shift+F10 on your keyboard. A a command prompt should open.
   If you can't find your usb drive letter, type the following command
      wmic logicaldisk get deviceid, volumename, description 
   Switch to you Windows 10 Setup USB/Disc and change to this folder.
   Sample: cd /D E:\Win10Lite

4. Run file rmApps.cmd and answer the questions for your needs.

5. Close the command prompt and finish Windows 10 Setup.
