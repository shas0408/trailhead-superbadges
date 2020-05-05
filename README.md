# trailhead-superbadges
#### Keeping a track of Metadata changes made in each Superbadge.


### Why am I doing this?
 - Why not? 
 - Also because [Trailhead](http://trailhead.com/) recommends using a new Trailhead Playground for each Superbadge.

   This way, I can just deactivate them myself and if I (or anyone for that matter) ever need these changes back, I can just spin-up a new Playground, deploy the metadata, create (or upload, haven't thought of that yet) the data and I should be good to go.
 - Also because I wanted to explore [ANT Migration Tool](https://developer.salesforce.com/docs/atlas.en-us.daas.meta/daas/meta_development.htm) and [SalesforceDX](https://developer.salesforce.com/platform/dx).

   What better project to explore these deployment tools than ~~documenting~~  versioning (:wink:) Superbadges on my Salesforce journey?


### How?
I am using [Ant Migration Tool](https://developer.salesforce.com/docs/atlas.en-us.daas.meta/daas/meta_development.htm) on a Ubuntu Server 20.04 hosted on a Hyper-V VM in my local machine. This virtual machine configuration is just so I can isolate the environment from my local machine.

I access the VM over OpenSSH using Powershell and keep on adding the files to my package.xml for retrieval.


### Superbadges I have worked on so far?
1. Business Administration Specialist

![enter image description here](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/superbadges/superbadge_business_specialist/8cd7fb96fbb29e613701dfeabc572327_badge.png) 


### What Next?
- I plan to keep on exploring Ant for a little while longer. At least until I have had my hands-on on all operation supported by Ant.

  Example: ~~Retrieve~~, Delete, Deploy, Deploy Code, Undeploy Code, Deploy Code with Specific Tests, Deploy Code with All Tests.
- I would probably be installing [Samba](https://www.samba.org/) in the VM so that I can edit code and package.xml from the host machine itself and just have to login to VM for issuing ant or git commands.
- Once I am confident with Ant, I'd move on to experimenting with SalesforceDX.


### Is that it?
Yep. That's it.
