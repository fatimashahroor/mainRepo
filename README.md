# mainRepo
Three repositories (repoA, repoB and mainRepo) were created first on github. 
The submodules of repoA and repoB which are respectively repositoryA and repositoryB were created inside the mainRepo as "mirrors". 
Then client.py and server.py were created inside repoA and repoB consecutively.
The submodules then were updated to include these files (using git submodule update --remote).
PyYaml library was installed in the original repos (repoA and B) using pip intall PyYaml.
Yaml configuration file was created in the mainRepo and variables were assigned to control server.py and client.py.
Client.py and server.py were implemented in a way to consume the boolean presented in the Yaml configuration file.
**To be done: a script that will be used for pushing modifications to both original repositories A and B and updating the corresponding submodule with the latest changes.