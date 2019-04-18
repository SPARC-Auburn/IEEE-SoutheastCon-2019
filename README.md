# IEEE Southeastcon Hardware Competition 2019
Welcome to the project repository for the Student Projects and Research Committee.  This is where we collaborate on technical aspects of the competition.  We use Gitlab as a git repository, task manager, and documentation manager.  The competition will take place at the annual IEEE Region 3 Technical, Professional, and Student Conference in Huntsville, AL from Thursday, April 11th, 2019 through Sunday, April 14th, 2019.

## Competition Description ("First 50 ... Next 50")
<img src="General/Images/SEC2019Perspective-450x300.png" alt="competition arena" width="300px"/>


The competition this year is set in the year 2069 where there are colonies on the Moon and Mars and 100 years since man first walked on the moon  The arena is an area in space where there are space hotels (aka. spacetels).  The spacetels (industrial status lights) are surrounded by space debris (2" wooden blocks and 2.5" ball pit balls). We are tasked with building an autonomous robot within the maximum size of 9" x 9" x 11" to clear orbital space debris while avoiding Spacetels and return to home base within the time limit of three minutes. The score is determined by a number of factors including: 1)the number of complete playing field orbits, 2) the number and type of space debris cleared, 3) sorting cleared debris, 4) returning to assigned corner square (home base), and 4) avoiding collision with Spacetel.  In order to make the robots easier to test, the first competition will be held on Earth in April of 2019.  The competition robots will be placed under the gravitational acceleration of 9.80713 m/s^2 and the atmospheric pressure of approximately 14.70 lbs/in^2. The arena will have wooden walls of dimensions 96.125" x 96.125" and have a thickly woven black textile as the ground surface.

Derived from the latest [competition rules](2019-SoutheastCon-HW-Rules_v1_1.pdf).

## Team Meetings
TBD

## Team Leadership
**Team Lead:** Matthew Castleberry (@mcberry23): mtc0030@auburn.edu  
**Electrical Lead:** Josh Jablonowski (@jdj0019): jdj0019@auburn.edu  
**Mechanical Lead:** Alex Jones (@alextigernick): naj0016@auburn.edu

## Other Resources
* Repository Wiki: https://gitlab.com/SPARC-Auburn/IEEE-SoutheastCon-2019/wikis/home
* Team Slack: https://sparc-auburn.slack.com/messages/CA8FS1MUY/
* Competition Website: http://sites.ieee.org/southeastcon2019/program/student-program/
* Team Website: http://sparc.eng.auburn.edu/

## Contributing Guide
### Using Git
How do you keep up with files on large collaborative projects without losing changes due to files overwriting?  You can use Git.  Git is a revision control system.  It allows you to clone(download) files of a repository (project) onto your computer from a server.  When you make changes to the files, you commit (announce) your changes.  You can then push (upload) your changes to the server.  You can use any git client you want to contribute.  Our favorites are [Linux Terminal](), [GitKraken](), and [Windows GitBash]().  SPARC uses the git hosting services GitHub for all public repositories and Gitlab for all private repositories. Git is not too hard to master once you understand the basics.  It does not require any programming experience to use Git.  If you want to learn more, check out our Maker Training Session [PowerPoint](https://github.com/SPARC-Auburn/Documents/blob/master/Presentations%20and%20Meeting%20Notes/2017-2018/01-23-18_MT_Git.pptx) from January, 23, 2018.

### Task Management
Gitlab has the ability to track [issues](https://gitlab.com/SPARC-Auburn/IEEE-SoutheastCon-2019/issues).  Issues are a way to record a note about something that needs to get done on a project.  You can place labels on issues to classify what they are or in our case what aspect they belong to: mechancial, electrical-hardware, or electrical software.  You can also assign them to individuals as well as set a deadline.  Milestones can be used to set common goals between issues.  Boards are used to keep track of which issues have been started, in progress, or closed (completed).

### Markdown and Documentation
What is a .md file and how do I do fancy text formatting without a tool bar.  Markdown is a lightweight markup language.  It is different than a WYSIWYG editor like Microsoft Word.  Instead you can use special characters to format text.  You can include links, pictures, videos, tables, and even [flowcharts](https://mermaidjs.github.io/) in markdown.  Gitlab has a really good page that describes how to use [markdown](https://gitlab.com/help/user/markdown).  The best way to learn markdown is look at examples and at documentation.  Gitlab's Wiki utilizes markdown through the browser.  We put all of our ideas and meeting notes into the [Wiki](https://gitlab.com/SPARC-Auburn/IEEE-SoutheastCon-2019/wikis/home).

### Mechanical Development
Mechanical development involves designing and manufacturing the mechanical system of the robot.  This includes everything from the mobility system and framework to the mechanism that collects the cubes.  We have many tools to our disposal from physical tools and 3D printers in our lab, to the free student edition of the professional design tool, SolidWorks.  To find out more about how you can contribute to the mechanical development see the [mechanical readme](Mechanical/README.md).

### Electrical Hardware Development
Electrical hardware development consists of choosing the sensors, computing device(s), battery, and other electronics.  It involves researching how the components operate and getting them to work together.  The electrical hardware is what links the mechanics and the software of the robot.  Right now, we are planning on using a Raspberry Pi 3 B+ as our single board computer to control the robot.  To find out more about how you can contribute to the electrical development see the [electrical hardware readme](Electrical-Hardware/README.md).

### Electrical Software Development
Electrical software development is focused on writing software to simulate and run the robot.  Right now, we are using C++ and Open CV running on Raspbian Linux as the main tools for operating the robot.  We are using [Gazebo](http://gazebosim.org/) to simulate the robot to test code, mechanical design, and algorithmic strategy. To find out more about how you can contribute to the electrical development see the [electrical software readme](https://gitlab.com/SPARC-Auburn/ieee-2019-electrical-software/blob/master/README.md).    