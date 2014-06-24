daily-log
=========

Simple scripts to record daily activities, usually in [Markdown](http://daringfireball.net/projects/markdown/), but just as easily in text.

To use, clone the repo into your working directory.

	$ git clone git@github.com:technmsg/daily-log.git
	
Daily Log
---

To start a new entry:

	$ ./new

A new file will be created in `./daily/YYYY/MM` and be opened for editing.

Weekly Summaries
---

To generate weekly summaries:

	$ ./gen_weeklies
	
Note: summaries are deleted and recreated each time; slightly inefficient, but okay since everything's being committed to git at the end of the week anyways... right? 
