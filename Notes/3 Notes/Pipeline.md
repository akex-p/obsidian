### Basics
- Asset = reusable production data
	- Has a structure
	- Immutability
	- Instance-ability
- Shot = sequence between two cuts/edit
	- Container for assets (Lighting, Animation, ...)
- Sequence = group of shots
### Categories
- Pull
	- Artists decide when to version up (e.g. Modeling)
	- All references/complete chain needs to update (Shading, Rigging, Texturing, ...)
- Push
	- "Masterfile"-Approach
	- Push change to everyone
- Hybrid
	- File Version 0 = Masterfile = Push 
	- Higher Versions = Pull
	- Artists choose
### Folder Structure
- Root
	- Group
		- Item
			- Task/Step
				- Type (Work/Publish)
### Additional folders
- User (for each user)
- Lib
- Pipeline
	- Plugins
	- Scripts
	- ...
- Edit
- IO (for external)
	- from_team
	- to_team
### Tips
-  Version Control is not standard in film (!!!)
	- Keep multiple versions
	- Not everyone works on latest version
	- Easy going back-and-forth
	- **Different for games**: use latest assets for running game
- Create Template: folder structure + .txt-files as dummy
- Never reference work files
- Create as many versions as you want (Work)
	- But: Publish = Version up work-file
- Masterfile
	- Very destructive
	- *Can* save time
	- Fine for smaller teams (!)
### Dos and Don'ts
- Use versioning patterns (e.g. v001, ...)
- Version up !
- Never reference files from your local drive
- Turn on auto save
- Setup backup-workflow
- Never touch publish files
### First Steps
1. Version für alles festlegen
2. Starter Files (.bat) festlegen
	- Possibility: Launcher
### Important Components
- Publisher
- Updater
- Review
- Render Farm Automation
### Cool Software
- REZ
- Conda
- Pyblish
- Royal Render
- Flamenco
### Useful Links
- [Pipeline Patterns](http://pipelinepatterns.com/intro/welcome.html)