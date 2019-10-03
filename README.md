# TRD-SermonSearch

The following is a general outline for a minimum viable product for the proposed SermonSearch functionality.  

This project being proposed will be worked on by all desiring members of “The Reformed Devs”, and will be an open source project under an MIT License. Being proposed as a #hacktoberfest project, the timeline, and thus overall goals will be quite condensed.

## Primary Goals

The primary goals for this project will include:

* Scraping and storing data from the website http://sermonaudio.com
* Allowing for useful searches based on as many data points as possible.

## Technologies and Approach

After a quick and informal survey of the parties desiring to participate the following choices in technology have been made.

This will be a hosted application, sitting primarily on top of a stack of PostgresQL, Node.js, and React.

Additional applications will sit outside the main application for data scraping, which will be written in whatever language provides the participant the most comfort. Both C#, and Python have been suggested, however, the choice remains to the participants.

The project workflow will be by means of Kanban on a Trello board.

## Storied Expectations

* User should be able to come to a single point and perform a search
* User should be able to search by
* Speaker
* Scripture
* Sermon Series
* Church / Location
* Media Date
* Category
* Topic
* Video / Audio
* Other - TBD
* User should be able to sort and filter results
* User should be able to click through to SermonAudio

## Aspects TBD

There are several aspects, yet to be determined, including but not limited to:

* Who will be in charge of hosting
* Where will hosting take place
* Wireframe designs
* What data is to be scraped and collected

## Final Proposal for MVP

The minimum viable product should have a functional front end with a usable, efficient, and adaptable search allowing end users the ability to search for sermons based on several datapoints surrounding sermons stored remotely on SermonAudio.

The minimum viable product should have consistent data updates via the means of scraping so that data updated, removed, or created on SermonAudio is mirrored in the local data storage.

## Future Features

Any other features will be considered unneeded for the initial deployment of the product, however, future features should be welcomed. As discussed by the group at large, bible study tools, and stored settings should be considered for future releases.
