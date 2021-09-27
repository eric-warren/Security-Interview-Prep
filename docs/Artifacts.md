<div class = "col-md-4">

### Recycle Bin Forensics:
    Location: C:\$Recycle.Bin\SID*\$Ixxxxxx Metadata
	          C:\$Recycle.Bin\SID*\$Rxxxxxx contents of file
	tools to parse: $I Parse

### RDP Cache Forensics:
	Data about parts of the screen
	stored in bitmap

	tools to parse: bmc-tools

### ShimCache/App Compatibility cache:
	Last update time / name and size
	no excution data anymore 
	
	tools to parse: ShimCacheParser
	
### SRUM (System resource utilization moniter):
	\System32\sru\SRUDB.dat
	app and user that excuted app
	app stats such as cpu, network, memory
	
	tools to collect: FTK imager/ volume shadow copy
	tools to parse: srum-dump

### LNK files (Shortcuts):
	created when opening a doc
	File path, timestamps, size, local or remote resourse
	can exist if target file doesnt
	
	Intesting location appdata/roaming/microsoft/windows/recent
		Recent files and folders
<\div>	
<div class = "col-md-4">
	
### Jump List (context menu when right click program in taskbar):
	conatins lnk files
	
### Shellbag (Folder view customization):
	in registry 
	shows folder has been visited by user 
	shellbags perist after file deletion
	
	tools to parse: shellbag explorer
	
### Event logs:
	Log parser can use sql queries to serach
	
	tools to parse: Log Parser, event viewer
	
### Persistence: 
	Run/RunOnce Reg keys
	Services: if service fails to start progarm is run
	DLL Search order highjacking
	Shortcut highjacking
	
	Tools to parse: Autoruns

### NTFS
	MFT Stores attributes

	Important attributes:
		Standard information: $SI user mode macb info + name and size
		File Name: $FN kernel mode macb info + name and size
		Data: stores small files less then 512 b
		Index Attributes: $I30 Duplicate File name timestamps + name and size

	Journaling:
		Transcational record of changes to volume
		Can show file was deleted
		USNJournal: $extend\$usnjrnl tracks changes to file in $J and 
		Logfile: $LOGFILE tracks changes to mft metadata
<\div>	
