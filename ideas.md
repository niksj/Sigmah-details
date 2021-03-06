#Project Ideas    
This project ideas list is just given as a suggestion. As written in the introduction, those ideas do however represent the short-term priorities of real users working in humanitarian NGOs. When describing a project idea, a User Priority is attributed to each feature request associated with it, to reflect its importance in the eyes of the users.

But user priority might not be GSoC volunteer priority… A new important feature requested urgently by some users may be felt as boring to develop by a GSoC volunteer. We just give those User priority because we believe that an exciting thing about contributing to Sigmah is that you're helping real users to work more efficiently in their daily work at managing humanitarian projects, and knowing where your help would be the most appreciated by users might be useful.

As a consequence, if a student wants to write its own proposal by mixing some of those projects or taking some inspiration from the [roadmap of the project](http://www.sigmah.org/issues/roadmap_page.php) , he's also welcomed to do so.

Finally, for each project idea, we provide a Development Difficulty level to give an hint about how easy or challenging it would be to deal with this idea.     

##Project idea 1: Full-featured calendars

Project Difficulty: Medium

**Presentation**

Sigmah already offers calendars for its users. But those calendars lack some advanced features and a higher level of integration between them, and integration with external calendar tools to reveal their full potential. As an example, when we make a demonstration of Sigmah to new users, 2 out 3 ask us: “Does the calendar integrate with Outlook?”.

More than a restrictive list of new features, this project idea reach to provide a richer calendar experience within Sigmah with a well-designed set of new functionalities. For example the exact way to provide the integration with Outlook is open to proposition to see which calendar should be exported: a new user calendar ? each individual project calendar ? And how then to limit the burden for the user to have too many calendars to export ? A good user experience is strongly expected and good propositions are more than welcome!

**Examples**

User Prority: 1

- [#521 Aggregating linked projects calendars](http://www.sigmah.org/issues/view.php?id=521)
- [#522 Aggregating sub-orgunits calendars](http://www.sigmah.org/issues/view.php?id=522)
- [#824 Calendars export to other devices](http://www.sigmah.org/issues/view.php?id=824)
- [#117 User aggregated calendar](http://www.sigmah.org/issues/view.php?id=117)
- [#78 Add a project and annual view in the calendar](http://www.sigmah.org/issues/view.php?id=78)
- [#852 Advanced calendar component](http://www.sigmah.org/issues/view.php?id=852)

User Prority: 2

- [#508 Merge "todo" and "pending" reminders](http://www.sigmah.org/issues/view.php?id=508)
- [#520 New date field option: saved in calendar](http://www.sigmah.org/issues/view.php?id=520)
- [#534 Field-linked reminders incentives](http://www.sigmah.org/issues/view.php?id=534)

**Impact**

The impact of the implementation of this project idea will be a better time management for NGOs: less forgotten deadline, less uncertainty on some key dates, etc.

**Knowledge prerequisite**

Java/GWT

##Project idea 2: Easier project model management

Project Difficulty: Medium

**Presentation**

Sigmah's most fundamental feature is the flexibility it gives to organization in the way they can configure it. With this flexibility provided through project models management, organizations are able to design their project information system by themselves, through a graphical interface they're able to use and not by configuration files which scare them in most of the case.

Sigmah flexibility is already provided a great service to its users, but it needs to be enhanced to reply to new needs expressed by users.

**Examples**

User Prority: 1

- [#853 Project/orgunit model export/import through an XML format](http://www.sigmah.org/issues/view.php?id=853)     
- [#514 Hypertext link in field titles](http://www.sigmah.org/issues/view.php?id=514)      
- [#276 Add a "Groups" tab in project/orgunit model management](http://www.sigmah.org/issues/view.php?id=276)     
- [#430 Delete group of fields](http://www.sigmah.org/issues/view.php?id=430)       
- [#511 Category modification flexibility](http://www.sigmah.org/issues/view.php?id=511)        
- [#854 Docked toolbar for project/orgunit model fields table](http://www.sigmah.org/issues/view.php?id=854)       

User Prority: 2

- [#390 Renaming project/orgunit default fields](http://www.sigmah.org/issues/view.php?id=390)        
- [#537 Fold by default option for groups](http://www.sigmah.org/issues/view.php?id=537)                        
- [#120 Multilingual project, orgunit, report models & categorie](http://www.sigmah.org/issues/view.php?id=120)       
- [#527 Twin fields](http://www.sigmah.org/issues/view.php?id=527)               

**Impact**

By developing a project idea of that sort, the GSoC volunteer will contribute to allow new usages of Sigmah by its users. It will help Sigmah adoption in wider parts of organization already adopting it.

**Knowledge prerequisite**

Java/GWT.

##Project idea 3: Search

Project Difficulty: Hard

Difficulty comment: Hard project idea for the full-text search engine (which is only user priority 2) becauxe it will require a knowledge of Apache Solr and strong capability to integrate with Sigmah. And this work with Apache Solr to produce a rich search engine has been estimated to a total of 74 man-days of work by experienced Sigmah developers: those 74 days might be reduced if we reduce the expectation of the full-text search engine, so it can fit in 12 weeks (60 man-days) time period of a summer of code.

**Presentation**

Currently, Sigmah offers almost no way to search among projects. Two features have been requested by users to improve Sigmah search capabilities (see examples below). And more can be imagined!

**Examples**

User Prority: 1

- [#536 Dashboard project table extra searchable columns](http://www.sigmah.org/issues/view.php?id=536)    

User Prority: 2

- [#535 Full text search engine](http://www.sigmah.org/issues/view.php?id=535)     

**Impact**

Improved search capabilities would dramatically improved the user experience and the perceived interest to use Sigmah.

**Knowledge prerequisite**

Java/GWT, and Apache Solr for user priority 2 full text search engine.
