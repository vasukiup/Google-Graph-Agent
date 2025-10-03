# Google Graph Agent
# learning from configuring the VS code to connect to Github are:

# setup Github - in this case Git is installed in d:\git\cmd\git.exe
# make sure that .git file is appearing under the project folder. view it in the explorer by enabling the view of hidden files.
# from the terminal check the status of git - git status, git --version.
# in case of any errors while checking status, you can use git init command to create the git folder.

# make sure that while setting the path, make the path as d:\\git\\cmd\\git.exe

# you need to set the git path in settings.json. it can be accessed from command pallette as follows
# Preferences: Open Settings (UI)
# it opens up a screen. click on the settings icon in the top right hand side.
# add the following "git path": "d:\\git\\cmd\\git.exe" in Settings.json file.
# reload the window using the Command Pallette->Developer:reload window option
# then search for the Git(from Microsoft) extensions in the VS code library
# make sure that it is enabled.
# reload the window using the Command Pallette->Developer:reload window option
# Now you would see the data from git repository loading into source control file.
# First pull the files and then make neccessary changes and then commit.