Command Line Tool
We've built a CLI (Command Line Interface) which is supported by OSX, Linux and Windows. To create your own resume, install resume-cli from npm:

sudo npm install -g resume-cli

Exporting
The command line tool uses an ecosystem of modules that we've open sourced to convert your resume to different formats:

resume export resume.pdf

resume export resume.html

Publishing
We have also built in hosted support into the command line tool. Much like npm's registry, you can register an account and publish to our servers. We also allow you to password protect and/or publish your resume anonymously. To get started, simply type:

resume publish

Our hosted solution will have new features and benefits rolled out quite frequently. Make sure you register if you want to save a vanity url:

resume register

Great! Your should now have your own url, like this: 
http://registry.jsonresume.org/thomasdavis

You can also access exported version of your resume: 
http://registry.jsonresume.org/thomasdavis.pdf 
http://registry.jsonresume.org/thomasdavis.txt

Users may also password protect their resume: 
http://registry.jsonresume.org/richardhendriks
