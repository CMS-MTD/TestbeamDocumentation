# Setup tracker operation


Setup two tabs like this:

	ssh otsdaq@athenanu
	cd /home/otsdaq/otsdaq/
	source cmstimingSetup.sh
		This file sets the save location for the raw data coming out of tracker.  (OTSDAQ_DATA)
	
	Then, one tab: execute RunController (from anywhere)
	Second tab: execute ots to start otsdaq

Note: Make sure all OTS process are killed



Tracker powering scheme:
<figure>
<img src="images/tracker1.png"/>
</figure>


