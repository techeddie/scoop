# Scoop package manager 
A beatiful command-line installer for Windows


### Set-ExecutionPolicy

	Set-ExecutionPolicy RemoteSigned -scope CurrentUser
		
### Install scoop
	iwr -useb get.scoop.sh | iex

### install packages

	scoop install git
	scoop bucket add extras
	scoop install notepadplusplus,brave,treesize-free,bat
	
	scoop cleanup *

### some useful commands

	alias       Manage scoop aliases
	bucket      Manage Scoop buckets
	cache       Show or clear the download cache
	checkup     Check for potential problems
	cleanup     Cleanup apps by removing old versions
	config      Get or set configuration values
	create      Create a custom app manifest
	depends     List dependencies for an app
	export      Exports (an importable) list of installed apps
	help        Show help for a command
	hold        Hold an app to disable updates
	home        Opens the app homepage
	info        Display information about an app

	
Website: https://scoop.sh/
