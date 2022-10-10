# Beacon Investigation
During the Antisyphon Threat Hunting Level 1 class (which you can find recordings of on their [YouTube](https://www.youtube.com/c/ActiveCountermeasures)), Chris Benton shares a couple of scripts he uses to make better use of the zeek logs. Because I have a Windows computer and don't have a network tap (and am not arp cache poisoning myself to get zeek to work) I use their tool Espy to get the logs. This means the scripts Chris has don't work out of the box.

These scripts that I have here are essentially the same as Chris' from the class, but there are both *.log and *.gz versions to accomidate the native way Espy saves logs. I also have versions that look at the entire `/logs/` folder as opposed to just a single day.

Huge thanks to Active Countermeasures and Chris Brenton for a fantastic free class!
