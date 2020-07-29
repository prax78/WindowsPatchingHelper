# WindowsPatchingHelper


This has two EXE files 1) GUI EXE 2) Client EXE

**How to use this**


1 Copy **"ClientFiles"** Folder to target servers, it has **"PatchDepot"** folder and the client agent EXE [**WindowsPatchingHelperClient.exe**].

2 Copy patches [MSU files] to the target server **"\\\\TargetServer\c$\ClientFiles\PatchDepot"**

3 Now run the GUI EXE from any server that can connect to your target servers over WMI[**WindowsPatchingHelperGUI.exe**].

 	 	A) Server.txt=> This must have servernames, one server per line.
		
  		B)RemoteEXE Path=> This is the location of WindowsPatchingHelperClient.exe on the Remote server.
  

![alt text](https://github.com/prax78/WindowsPatchingHelper/blob/master/WindowsPatchingHelperV1/patchtool.png?raw=true)

4 You can pull HotFix report by Clicking "Report" Menu Item post patching.
