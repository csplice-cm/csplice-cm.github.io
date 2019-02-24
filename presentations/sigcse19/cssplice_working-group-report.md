# Who are we?

* Austin Cory Bart - University of Delaware
* Phill Conrad - University of Santa Barbara
* Michael Hilton - CMU
* Bob Edmison - Virginia Tech

# Overview of the problem (4 minutes)

* Curricular Packaging: 
  * A broad set of tasks (creating, revising, sharing, finding, crediting, evaluating, etc.)
  * A broad set of materials (assignments, assessments, slides, teacher notes, evaluation data, etc.)
* We need fewer barriers for the tasks and better structures for the materials
  * A course is way more than a deck of slides and a syllabus
  * Probably not going to be solved by a single new piece of software!
* Rundown of various common scenarios
  * Instructor needs to find a ready-to-go lesson on topic X for his course
  * Instructor wants to share a good lesson
  * Instructor wants feedback on a lesson they shared
  * Instructor wants to modify a lesson they've been using based on some suggestions by an adopter
  * Instructor wants credit (e.g., for promotion) for the number of adopters of their materials.
  * Instructor wants to take a specific colleague's set of materials, with changes
  * Researcher wants to analyze course materials
  * Researcher wants to find out if two courses using their tool are similar enough to compare
  * Instructor wants to share experiences about a course, including some student-generated data
* We have a longer [White Paper](https://docs.google.com/document/d/1gvbfjz4_at1fmAUfR02dOP1WycM63iV_jML-osnQT9c/edit) that goes into some depth

# Issues (2 minutes)

* Non-standardized Goals: Very little is common across Computer Science, even in our CS1 courses.
* Novice Designers: Most CS instructors have no real pedagogical training or knowledge of instructional design.
* Tool Lock-in: A lot of materials end up locked into a tool, by necessity or choice.
* Lack of Incentives: There are limited motivations to spend time developing stuff for sharing (credit for promotion, simplifying our lives, money?).
* Misguided HCI: We often end up catering to power users rather than making stuff simple and accessible for the 80% of normal users.
* IP Policies: Different institutions have different rules about what you can share with regards to materials.

# Discussion of existing efforts (2 minute)

* [Ensemble](http://www.computingportal.org/): Somewhat older "free digital library" of tools and curricular assignments, kind of limited in scope. Talking to some of the folks in charge of it, I am unclear what its future will be. For now, it exists, but I don't know that it represents a major future effort.
* [Nifty Assignments](http://nifty.stanford.edu/): A collection of high quality assignments that has become its own track at SIGCSE. Most of the assignments are lab/project scale, so this represents a narrow slice of curricular materials. Although their focused, they probably have some good lessons learned.
* [EngageCSEdu](https://www.engage-csedu.org/): Curated collection of curricular materials, recently instituting more formal peer evaluation models that show promise. *(acbart: Some of these folks have reached out specifically interested in working with us.)*
* [Leake & Lewis '17](https://dl.acm.org/citation.cfm?id=3017780): SIGCSE’17 paper with guidelines and notes about developing CS resource sharing sites, targeted at K-12 space.
* OER and Learning Objects are the existing subfields in Education
* Other projects are more narrow slices of packaged curriculum:
  * OpenDSA, Canturbury Question Bank

# Description of proposed format (4 minutes)

Our current vision to start tackling this problem:

* Develop and promote a Git-based format for courses.
  * Build curricula material templates in plain text formats (YAML/Markdown)
  * Develop converters from/to common LMS and import formats (e.g., Common Cartridge, Canvas API, PEML)
* Develop a shared vocabulary to promote best practices
  * Taxonomy and definitions for various Nouns ("Lesson", "Module", "Assignment", etc.)
  * Definitions and formal processes for various Verbs ("Creating", "Sharing", "Evaluating", etc.)

# Description of Best Practices documentation (2 minutes)

* How to follow an Instructional Design process for developing your materials
* Organizing public, private, and secret data
* Advertising with/directly using GitHub Pages
* How to streamline IRB/FERPA/IT Security interactions to be compliant
* How to evaluate your materials
* How to get feedback on your materials
* How to get promotion/tenure credit for your materials

# Major steps for breakout:

* What are our pain points with curriculum packaging right now?
  * How frequently do we encounter each type of pain points?
  * What scenarios did we miss?
* How have you been solving these problems so far?
  * Specific processes you follow
  * Specific tools you've developed or use
  * What are your colleagues doing?
* What motivations do you need with respect to curriculum packaging?
  * Money? Tech support? Pedagogical support? Promotion credit? Public accolades?
* When considering tools to help you with this, how much do you prefer automation vs. manual effort?
* What repositories, projects, and research should we know more about?

# Where do we go from here?
* Short term:
  * Join our [Google Group](https://groups.google.com/forum/#!forum/cssplice-curriculum-packaging-working-group)
  * Review our candidate solutions
  * UCSB Jekyll theme for Git courses
  * Waltz - tool for moving course material between Canvas and a Git repo
  * Answer our Google Form (forthcoming) about pain points in Curriculum Packaging
* Long term:
  * Write up our specification and best practices
  * Have one or more repositories adopt our format (CSEngageEdu?)
