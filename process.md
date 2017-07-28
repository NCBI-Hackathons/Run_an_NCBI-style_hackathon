# 1. Organizing and setting up the hackathon
```Written by: Peter Oxley```

## 1.1 Creating hackathon projects
#### Identifying the goals of the event
* development of useful applications, code libraries, databases.
* networking and establishment of long-term, inter-disciplinary collaborations.
* education of participants in application development process
* building teamwork and leadership skills (hackathon process can be adapted for other domains, such as in a laboratory setting (especially in computer science), where postdocs become team lead for a week-long hackathon in lab, with the lead rotating through all postdocs in the lab.

**By request: Some people will have projects they want to lead**
Seeking out people that have a project they would like to contribute to in the hackathon environment provides several benefits for the organizer. 

* The topics come with a better-defined scope.
* There is an obvious choice for team lead (this is not necessary however, if a more experienced team lead with relevant background knowledge is available for the project.)
* There will be someone on the team that has a high level of knowledge

* Questions to ask to develop a project (and to help identify potential participants):
    * Project Description
        * What need will your project fulfill? 
        * What do you want its functionality to be?
    * General Project Goals 
        * What do you want the end product to be? 
        * how do you want to get there?
    * Team skills
        * What are your strengths?
        * What types of skills might you rely on your team members for?
    * Resources
        * Atypical software the project will require.
        * Compute resources required: RAM, disk space
         
**By relevance: How do we define a good problem**
Especially for hackathons designed to introduce people to the process, it is useful to deliberately design projects that do not require prior bioinformatics, programming or software experience. These projects can be flagged as "low-hanging-fruit". Examples include documentation updates, clarifying error messages, copying and modifying tests.
 
## 1.2 Gathering participants
#### Advertising
Reaching all the relevant people. How early should the advertising begin?

* blogs
* social media (Twitter, facebook, etc)
    * identify social groups to target announcements to
* conferences
* project lists, listservs
* web page
    * NCBI hackathon has a specific web page to list all confirmed hackathon events


#### Inviting


* Forms: Data to collect:
    * questions from June Hackathon's form
        * Do you have a working knowledge of shell scripting?
        * What other programming languages do you have experience with?
        * What is the primary research question you work on?
        * Are you interested in working on a similar problem during this workshop?
        * Please tell us in 3-4 sentences why you want to participate.
        * Here are Some Approximate Project Titles (which are expected to evolve); which are you interested in working on?
        * What is your email address?
        * What is your name?
        * What is your approximate geographic location?
    * Making them machine readable: checkboxes over free text
 
* Other considerations
    * adding all communication to the github page, ensuring that all users have an account set up.
    *  
 
#### Filtering
* Criteria
    * basic knowledge of command line
* Number of participants - factor in a 10% drop-out rate when creating inclusion list
    * Create an A, B and C list, so that when an individual drops out of the event, there is a shortlist ready to bring in a replacement quickly.
    

* Required knowledge - depends on the topic. 
    * coding language
    * software knowledge
    * research domain knowledge
* team leads could be involved in this process?

* Identifying team leads. These people will organize, delegate and ensure effective communication among team members. The following attributes will frequently indicate a good choice for team lead:
    * author of project proposal
    * prior experience leading hackathon teams
    * prior hackathon participation
    * domain expertise (software, coding or scientific)
    
    
## 1.3 Creating a schedule
#### Basic elements
**Time** - how long to have a hackathon?


| Option | Pros | Cons |
|--------|------|------|
| 24 hr model. |  Less up front commitment, since it is over after a day (though need time to recover?) |  Problem with productivity - what are people really doing at 2am? |
| 3-day model |  Everyone gets to sleep, focus productivity during day. | Harder to recruit, since participants have to take three days off work, other work builds up. |
| ---   | Time for socialising and team building | --- |



#### Example schedule

```
Day 1
9:00 - 9:30:    Introductions, Administrative Announcements and Building Functional Software
9:30 - 9:45:    Technical considerations when using the Amazon cloud for high throughput data analysis, and some more introductions.
                Technical note: Move tools (with git) not data (I know everyone says that, but we mean it this time).
                Technical note 2: Why we are using GRCh38 for this project.
                Split into locations for teams (see below)
9:45 - 10:00:   Role assignments in teams
10:00 - 12:15:  Sysadmins and Data Acquisition get data, if necessary
                Everyone else work on first sketch of plan (one page google doc, or similar)
                All teams return to main location
12:15 - 1:00:   Working lunch and sharing of initial searches and discussion between groups (catered lunch opt-in 1; see poll)
                Split into locations for teams (see team spreadsheet -- tab "locations)
1:00 - 6:00:    Pipeline building [script building]
                NCBIrepresentatives present to help with pipelines
6:00 - 7:30:    DINNER (on your own or with group members)
7:30 - 8:30:    Implement any remaining code/start pipelines (remote is an option) [script building]
 
Day 2
9:00 - 9:15:    Presentation: 
9:15 - 12:30:   Data cleanup, code fixing, and presentation generation
12:30 - 1:30    Working lunch (catered lunch opt-in 2; see poll) Each section presents four slides; opportunity for exchange of ideas (and personnel if necessary)
1:30 - 6:00:    Pipeline fixing and implementing suggestions from other group; more data runs
2:30            Coffee break (Location)!
4:00 - 5:00     Writers group breakout 1
6:30 - 8:30:    GROUP DINNER (see poll); opportunity for feedback on organizational structure and future projects
 
Day 3
8:30 - 9:00:    Breakfast on campus -- more opportunity for feedback on organizational structure and future projects
9:00 - 9:30:    Quick tour of SRA BLAST (NLM Visitor Center)
9:30 - 12:00:   Finishing pipelines
12:00 - 1:00:   Working lunch (catered lunch opt-in 3; see poll)
                Meeting with Senior Staff
1:00 - 1:10:    Potential for transferring data to helix/biowulf
1:10 - 5:10:
                Writers break off for writers group
                Editorial representative from library will be there to assist.
                Everyone else documents code and writes READMEs
                Pipeline testing!
                Bug fixes
                Presentation generation
                Upload code to Github and/or Bitbucket and/or Coders crowd and/or Docker!
4:45 - 4:55:    Marketing, community interaction, and longevity of code
                Who is going to deal with future pull requests?
                Awards ceremony!
5:00 - 6:45:    Final Presentations (5 slides per group)

```

## 1.4 Preparation of resources  
#### Information sheets, instructions and tutorials

* instructional "how to" for beginners. Include all the fundamental processes useful in a collaborative computing exercise, including:
    * cloning a repo to local computer
    * creating and claiming issues
    * committing changes
    * pushing changes to repo
    * documenting changes
* manuscript template for F1000 submission, making publication writing an integral part of the process. 



#### Computational environment
__see chapter on technical issues__

* User access
* User privileges through central manager vs free for all

#### Data sets
For testing 
 
#### Libraries and software
Common workspaces for documentation collaboration

* google doc set up for the manuscript (eg F1000) template
* F1000 workspace subscription, with teams established
    * allows teams to save bibliography
    * allows citation and bibliography generation in google docs

Identifying existing software/libraries that can be built upon
 
# 2. Running the hackathon
The majority of projects will cease to be developed at the end of the Hackathon. Therefore, it is paramount that by the end of the event, the code is deposited in a public repository, developed to a useable degree, and well documented. 

## 2.1 Coordinating the event (aka maintaining momentum)
* Keeping enthusiasm high is key. Once a team loses motivation, productivity will plummet. If people leave (for negative inter-personal reasons), it will be disastrous for team morale and productivity. 
* Event coordinator must identify team communication blocks early, and have the ability to diffuse tension and facilitate problem solving.
* The coordinator will not have the capacity to become deeply involved in the development or troubleshooting of any given project. They will not likely do any but the most cursory of coding.
* Coordinator should be aware of their audience, and the expected etiquette for interaction (eg, appropriate dress code for coordinator - typically slightly more formal than the average expected participant).
* Will need to keep track of who may decide to leave, and identify the issue that caused the participant to make this decision. It is then the coordinator's responsibility to ensure that the issue is addressed.

## 2.2 Documentation 
Documentation allows code to be understood, installed and used, debugged and error checked, and extended. Without documentation, an application is unlikely to become utilized by the research community. However, documentation is frequently a low priority of development teams. It is therefore important for the event manager/coordinator to build into the program education about the importance of documenting things, education of people in how to document, and sessions to inspect the current level of documentation, and to provide correction.

Elements that need to be documented include: 
* 1 sentence description/summary of the project
* implementation button - get to the application obviously and easily
* link toc to all elements

* description
* background
* Code link
* Package dependencies
* Installation instructions/implementation
* Usage instructions
* Data formats and standards applied
* lots of images of results



#### Assign document writers in each team
Each team designates a writer to ensure documentation is captured and published.

#### Tracking documentation progress
Implement writer breakout sessions to ensure documentation is on track, following appropriate standards, troubleshoot any issues.

* Discussion of Output
    * Update sessions / group presentations
    * Github
        *  Live cloning of repos
    * Publishing
        *  Journal Strategy Selection
        *  Advertising and social media

## 2.3 Meal breaks 
Maintaining hydration and blood sugar levels is important for focus and productivity. Thus it is important to stress to participants the need to take breaks and eat and drink. This will be more likely adhered to if nutrition is easily available and/or free.

####################
* Metadata
* Data Acquisition
* Data Normalization
* Downstream Analysis 
    * (Statistics)


# 3. Hackathon follow up
## 3.1 Publication
* Provide F1000 template for all teams to build their ms during the event.
* Make sure there are figures!
* Don't forget suggested reviewers

## 3.2 Surveys
#### Discussion points collected during hackathon (via face-to-face and Slack channel):
 
## 3.3 Debugging, polishing code, testing

## 3.4 Handing on the baton
This section deals with how to ensure that the code can continue to be built, tested, improved and extended. This process begins during the final hours of the hackathon, and is in some respects never finished. But there are certain milestones that can be set in terms of finalizing the effort begun during the day(s) of the hackathon:

1. Assigning who is responsible for administering pull requests, and reported issues.
2. Finishing testing and debugging with sample datasets
3. Publishing the package in an open-science, peer-reviewed journal (eg. F1000)
4. Handing over or leading extension at the next hackathon