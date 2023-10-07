# Thursday - Track 1 - 4pm

## The Great Task Heist

> Brandon DeVault | Pluralsight | devaultsecurity.com

---

## Raw Notes

- How to threat hunt for anomalys scheduled tasks.
- MITRE persistence technique. 132 known groups use this.
- Sysmon can track new scheduled tasks.
- %systemroot%\system32\Tasks -> XML files for each scheduled task.
- Can also pull scheduled task information via Powershell.
- 148 default scheduled tasks on an Amazon EC2 Windows instance.
- Attempt to pull from local machine into Elastic:
	- XML -> JSON -> Elastic
	- Logstash pipeline
	- XML parser
	- ^^ Fails.
	- "SaveJSON2CSV" - workish.

## Thoughts/Observations

I was really hoping to get a more apt use-case and operation out of this talk. Very good information and definitely points me in the right direction to improve my own threat hunting operations. An audit of scheduled tasks would be a good thing to do as part of my security assessment. Maintain a database of known good scheduled tasks and compare/contrast. 
