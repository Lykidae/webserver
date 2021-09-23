Title: The Story of this Website
Date: 2021-05-23 21:26
Category: tech
Summary: Why and How this Website Exists
Cover: /images/MilkyWay.jpg
Author: Nickolos Monk

This Website was an exploration into system administration and data management. Below I will outline the steps I followed to create this website.



First, I got an AWS-ec2 instance, and configured the security groups so that it could accept HTTP/HTTPS traffic.  

Then, I created a set of playbooks with Ansible, the tasks including:
	1. Installing and Configuring the services.  
	2. Getting updates from a version-controlling service (in my case, GitHub).
	3. Sending data to a data management service (Splunk).

I use Pelican to write blogposts in markdown, and make small adjustments to this website manually by modifying the HTML that Pelican produces.

Finally, I use Splunk to monitor traffic to/from my Website, and use it to detect and report suspicious traffic and alarm-worthy HTTP Requests!

While not the craziest of projects, it was a fun one that helped introduce me to many tools. I've got a lot of ideas for them, so stay tuned and I may end up publishing some more things! My next project is to get industry certified, and immediately after, collect data from my car and publish it on this website.
