# servicenow-mid-servers
MID Server Installation and configuration

MID - Management Instrumentation Discovery :
MID Server is a light weight Java application that runs as a windows service or Unix daemon on a server in your local network.

MID Server has it's own "Internal IP Address" to communicate with customer's environment. This is not the external IP Address that is used to connect out to the internet. MID Servers will not be pre-validated, It must be validated after Installation.

After validation, we need to specify the capabilities like applications and IP ranges.

1. Applications that use it 
2. IP ranges it is allowed to explore.

Note: When a MID Server is upgraded that is already configured in your instance are automatically validated to prevent interruption of automation tasks that MID Servers might be performing.


