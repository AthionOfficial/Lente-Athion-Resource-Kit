# The Lente/Athion schematic kit project
This resource kit will strive to be a forever growing resource kit of publicly submitted and privately curated schematics.  This kit will strive to be the largest repository of schematics which will ideally cover a vast variety of terrain detailing schematics.  The beginning will likely consist of initially the Lente tree-pack and hopefully some evolutions and expansions of said pack.  Then will hopefully use this as inspiration to grow expand and improve upon this pack extending from trees to rocks, fantasy flora, mushrooms, shrubbery, statues, houses, dungeons, mines, caves, coral, seaweeds, shipwrecks and many many more.  The limit is only the creativity of the people submitting schematics.

We will have a private team of curators who will ensure the quality, completeness and categorical correctness of each submission made.  

## Redux
<!-- TOC depth:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [The Lente/Athion schematic kit project](#the-lenteathion-schematic-kit-project)
	- [Redux](#redux)
	- [GitHub and why we're using it](#github-and-why-were-using-it)
	- [Our goals](#our-goals)
		- [Simplicity](#simplicity)
		- [Organization](#organization)
		- [Automation](#automation)
	- [More Technical details on Automation](#more-technical-details-on-automation)
	- [Committing changes to the Lente-Athion-Resource-Kit](#committing-changes-to-the-lente-athion-resource-kit)
		- [Committing via the Lente-Athion-Resource-Kit server](#committing-via-the-lente-athion-resource-kit-server)
		- [Committing changes on your own via GitHub](#committing-changes-on-your-own-via-github)
<!-- /TOC -->

## GitHub and why we're using it
This entire pack will have its own github repository so that its existence can outlive the existence of any particular server so that these resources will forever belong to the entire community.  This will also be intended to outlive the existence of websites that rely on people to maintain them and pay for them since GitHub is likely to outlive interest groups as well.

## Our goals
The goals of this pack will be to contribute basic resources to improve and establish a new base level of Minecraft creative productions.  We want to help people avoid the monotony of re-creating the same things over and over again delaying the completion of their own projects.  Concerning themselves with detail work that is unnecessary in most cases.

### Simplicity
We wish to keep the process as simple as possible keeping it simple will be the key to the ongoing success of this project.  This means we will likely not be varying our methods very much once established as we wish to maintain our automation as best as possible.  

### Organization
We plan to make organization simple and consistent.  This will prove to be a difficult task since we plan on extending much further than just simply trees so we will need to establish an clean and concise directory structure that isn't so overly complex that no one will maintain it. A possible example will be.

* trees
  * North_American
    * Cedar_tilt_sw.schematic
* shrubs
  * Flowers
    * Rosebush_straight.schematic
  * Hedges
  * Ground_Cover
* objects
  * rocks
  * Boulders
* statues
  * Dragons
  * Gargoyles
  * Angels
  * Animals
  * people
  * Avatars
* dungeons
  * Desert
  * Jungle
  * Oceanic
  * Aztec
  * Egyptian
  * Medieval
* houses
  * Medieval
  * Nordic
  * Modern
  * Contemporary
* hospitals
* castles
* temples
  * Catholic
  * Roman

### Automation
Because of the need to ensure that the publication of schematics to the Resource-Kit is never delayed we will be striving to automate this process as best we can so that once a schematic is submitted the curators can come in and approve improve or deny the addition to the Resource-Kit.  

## More Technical details on Automation
When a schematic is `accepted` to the Resource-Kit it will have the `username` of the `submitter` added to the `git commit` message for that schematic.  Once every week a crontab job will run attempting to push any changes to the remote repository.  If there has been no changes then nothing will change but sometimes there may be several changes committed in one push.  

We will likely export each schematic into a directory representing the root category.  This is because it will likely become very large and complex so adding 50 different types of schematics directly into the root of the Resource-Kit will become confusing and just simply horrible to organize.  

## Committing changes to the Lente-Athion-Resource-Kit
There will be two methods to add your own content to this Resource-Kit.  There are benefits and caveats to both methods.

### Committing via the Lente-Athion-Resource-Kit server
We've set up and designed a server designed to streamline the schematic submission process. This will be the only way to submit new resources to the kit.  Because we don't have time to sit here and download and inspect every single schematic by downloading installing and pasting in the schematics everyone brings us.  We will only be accepting schematics submitted directly into the Resource-Kit submission world.  

### Committing changes on your own via GitHub
You will need to fork this main repository and submit a `GitHub Pull-Request` for review.  The only reason to do this is to help improve the GitHub-pages branch of the resource kit or suggest imagery for each schematic if you wish to be so kind as to contribute photography of each schematic.  This is greatly encouraged as we likely won't have time to do this for each variant of each schematic.
