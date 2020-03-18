# JMeter Quiz Test Plan (jmeter-quiz-testplan)
JMeter test plan file for simulating the behavior of simultaneous quiz on the Moodle 3.x

Summary
------

This is a JMeter test plan file (JMX file) for simulating the behavior of simultaneous quiz on the Moodle 3.x.
By default, the start time range for students is 5 seconds, and the range for sending responses is 60 seconds.
The quiz has 20 questions.

Requirements
------
* Moodle 3.x.
* Apache JMeter.
* Oracle Java Runtime (or OpenJDK) 8.0 or later version.
* Non Windows PC (ex. Linux, macOS, etc.) for JMeter Client.

Installation
------

Please see installation manual.

Remarks
------

The JMeter does not interpret or display received web pages.
In actual operating environments, the time required for interpreting and displaying web pages is added.

Change log of JMeter Quiz Test Plan
------

Version 1.0 

* release first version.
