
# Principles

What do we understand as monitoring, which type do we differenciate?

## KPI - Monitoring

### Description/Definition
KPI Monitoring's purpose is to be able and/or to give a indication of the health of the system/application.

Therefore it should only consider a few basic indicators ( 3-5 kpi's ) which characterise the system or application and which will reflect the status of the system/application.

Setting-up is straight forward and easy.

### Stakeholders
SLA calculation tools
DevOps ( Operations)
Manager

### Mindset
Identify simple meaningfull characteristics/behaviour of a component (system or application).
Quick and Simple

### Tools
Monitoring tools with a basic sets of Monitors: Zabbix, scom, SNMP Agents/Systems, rdp, prometeus, splunk, windows WMI ....  

## Root Cause Analyses - Monitoring

### Description/Definition
Monitoring of applications with the purpose of finding the cause of a malfunction.

Therefore there might need to have multiple indicators, spread over multiple applications or systems. 

Setup needs a lot of know-how and resources as the ("complex") relationships between indicators should be known.  
Code injections migth be needed, "working paths" should be known/predicted or malfunctions/errors should be reproducable to be able to analyse.

### Stakeholders
DevOps ( Development)

### Mindset
Identify characterists/behaviour of a component and the dependencies and impact/influences on adjacent/connected componenents.
Isolate and/or reproduce a event/problem/behaviour.
What are you measuring and how are you measuring

### Tools
dynatrace, zabbix, prometues, aanpm
