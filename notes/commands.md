# Commands
Accepted Commands from the C&C server (according to ESET):

Name: GET_AGENT_INFO
Integer Value: 1
Purpose: Reports IDs and settings of modules and channels to the C&C server

Name: PING_REQUEST
Integer Value: 2 
Purpose: Reports IDs of modules to the C&C server

Name: CHANGE_PING_TIMEOUT
Integer Value: 31
Purpose: Sets the parameter defining the amount of time to wait before initially contacting the C&C server to the given value

Name: CHANGE_STEP_TIME
Integer Value: 32
Purpose:  Sets the parameter defining the amount of time to wait between two attempts to reach the C&C server to the given value

Name: SET_PARAMETERS
Integer Value: 33
Purpose: Saves the two previous parameters current values in the LocalStorage SQLite3 database, such that those values will be re-used at next startup

Name: CHANGE_CHANNEL
Integer Value: 41
Purpose: Changes the currently selected channel to the channel identified by the given ID

Name: CHANNEL_SET_PARAMETERS
Integer Value: 42
Purpose: Changes the settings of the channel identified by the given ID. For example, it may be used to change the C&C server address

Name: LOAD_NEW_MODULE
Integer Value: 51
Purpose: Instantiates as IAgentModule object from the given data, and registers this new module with the kernel

Name: UNLOAD_MODULE 
Integer Value: 52
Purpose: Unloads the module identified by the given ID 

Name: LOAD_NEW_CHANNEL
Integer Value: 53
Purpose: Instantiates as IAgentChannel object from the given data, and registers this new channel with the kernel

Name: UNLOAD_CHANNEL
Integer Value: 54
Purpose: Unloads the channel identified by the given ID

Name: UNINSTALL_XAGENT
Integer Value: 61
Purpose: Kills the Xagent process

**Sources:**
[https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf](https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyNDI1MjE3NjNdfQ==
-->