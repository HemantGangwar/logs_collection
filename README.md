# Logs Capture Script

## Description ##

This script can be used to capture logs from Linux or Windows based systems and can be run from either of Operating systems. 

Follow the steps given in Usage section to run the script. 

1. Upon execution logs captured from each server will be generated in same location where script is executed. 
2. 2 Files will be created for each server logs and the errors captured.
3. Also a file 'nodes_unreachable.txt' will be created containing list of unreachable nodes.
4. Total time taken for script to be executed will be displayed.

##* For fetching logs from Windows Client *##

Deploy openssh on Windows first: https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=powershell


## Usage ##

### Displaying help page of script ###

![image](https://user-images.githubusercontent.com/38517925/188445414-ccbd19cf-cc15-42be-9d51-9f1d793f5a14.png)

### Invoking script with list of servers stored in a file ###

![image](https://user-images.githubusercontent.com/38517925/188544517-f24f6240-c209-4c1e-8da1-f78961f33118.png)

![image](https://user-images.githubusercontent.com/38517925/188544548-9c510b5f-43b2-4907-9490-8c9fd76f2f56.png)

### Executing script on single host ###

![image](https://user-images.githubusercontent.com/38517925/188544576-933ac710-ddfb-4341-b908-dbd4bebcb56b.png)

### Executing over list of host mentioned inside script itself ###

![image](https://user-images.githubusercontent.com/38517925/188544689-c3f8a22e-666d-49f5-a4a7-6a307d63f140.png)

### Executing command on Windows EC2 from Linux ###

![image](https://user-images.githubusercontent.com/38517925/188575435-f0e1a426-a50f-4c22-8031-d24c760b3dbe.png)

