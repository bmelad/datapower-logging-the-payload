# Write the payload to the log

using IBM DataPower Gateway, sometimes its difficult to troubleshoot issues, because the Probe not showing the payload properly (or at all). A simple solution for that situations is just throwing the whole payload to the log.

This little GatewayScript will write the payload as an error to your log.


## How to use it?

Just drag this GatewayScript to your processing rule and call the relevant service.


## Need to change the log level?

If you've got a DataPower Operations Dashboard (or any other central logging solution), you may want to make the log level lower. it that case you can change the 'error' to one of the following values:
* warn
* log
* info
* trace
* debug

A full list of the console methods (and a formal reference) may be found at [IBM's knowledge center](https://www.ibm.com/support/knowledgecenter/en/SS9H2Y_7.6.0/com.ibm.dp.doc/console_js.html)
