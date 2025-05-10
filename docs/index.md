# Welcome to Team 5607 Programmer's Guide

The *Programmer's Guide* allows those interested in being part of the programming team to have a consistent setup and is intended for new programmers at robot in a weekend (RIAW)

###### To Summarize Setup:
1. Login to [Github](Github.com) / make an account
2. Get added to the team by a mentor / given write access to the repository
3. Download and install VSCode for [WPILIB]([[https://github.com/wpilibsuite/allwpilib/releases]])
4. (optional) Download and install Github Desktop [(windows/Mac)](https://desktop.github.com/download/) (Fedora: sudo dnf install github-desktop)
5. Clone repository for RIAW(robot in a weekend)
6. Download VSCode Extensions (see below)
7. Import project into VSCode and start programming!

## Getting Started

### GitHub UserID

* Make sure you have a [github.com](https://github.com) user id.
* You will need to get added to the *SEASON-YEAR*-Programming Team to be able to contribute.
* New to Git and Github? Check out this article for a basic intro on how to do code versioning with Github. [Github QuickStart](https://docs.github.com/en/get-started/quickstart/hello-world)

  
### WPILib.org
Firewall's programming team relies heavily on WPILib.org's set of tools and libraries to jump start our robot's programming. They publish updates with every season. So it's good to be familiar with their documentation and check for periodic updates during the competition season.  So go ahead and visit [wpilib.org](http://wpilib.org).
* [2023 WPILib Installation Guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)
* [WPILib GitHub ](https://github.com/wpilibsuite/allwpilib/releases/tag/v2023.4.3) Download page for grabbing current releases once you've installed WPILib's version of Visual Studio

### Fast track to becoming a Firewall programming Expert
Mentors recommend reviewing the following pages of the WPILib documentation to be program champions and decrease chance of frustration.
* [WPILIb Visual Studio Code Basics an WPILib Extensions](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/vscode-basics.html) The version of Visual Studio Installer that you downloaded from the WPILib Install site has some commands built in to help you program. This section helps you leverage them. Be sure to click through to the commands section.
*  [Creating a Robot Program](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/creating-robot-program.html) Overview of how to organize FRC Robot code. 
* [Building and Deploying Robot Code](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/deploying-robot-code.html#) You've got your code all written, now what do you do??? Just keep clicking through this section to learn how to build, deploy, and debug with WPILib and Visual Studio.

## Robot In A Weekend -*RIAW*  
  ### List of tasks:
   * Setup YAGSL for the RIAW robot [Documentation](https://docs.yagsl.com/) and [last years code](https://github.com/FirewallRobotics/A-Bot-2025-2)
   * Setup drive controls [Documentation](https://docs.wpilib.org/en/stable/docs/software/basic-programming/joystick.html) and [Last years Robot Container](https://github.com/FirewallRobotics/A-Bot-2025-2/blob/master/src/main/java/frc/robot/RobotContainer.java) (scroll to configureBindings)
   *   
  
## Continue on!
### That's all great, but I want to Specialize!!
Do you prefer to work with user interfaces? or are you fascinated by a world with image processing and machine learning?  The team can use your passion and interest working in either or all of these specialist areas...keep reading :)
* We want an out of this world control dashboard!! so we need experts on:
  * [ Dashboards](https://docs.wpilib.org/en/stable/docs/software/dashboards/index.html) WPILib has 4 to choose from. Elastic is the newest. Check them out and see what layouts you can create with them. Drive team will thank you!
  * [ DriverSation](https://docs.wpilib.org/en/stable/docs/software/driverstation/index.html#)
* Image processing so our robot can choose targets and assist drivers.
  * [ Vision Processing WPILIB](https://docs.wpilib.org/en/stable/docs/software/vision-processing/index.html) Documentation on everything vision (in great long detail)
  * [Limelight Vision Documentation](https://docs.limelightvision.io/docs/docs-limelight/getting-started/summary) Documentation on our current vision platform
* [ Hardware Tutorials](https://docs.wpilib.org/en/stable/docs/hardware/hardware-tutorials/index.html) How to make the motors go, understand sensor output, control pneumatic, etc. etc.

### Cross-train
We can't program the robot if the components aren't wired in correctly. Consider cross training with the Electrical team so that we can work more efficently. (or get a wiring diagram from Electrical)
* Check out this overview of [Basic FRC robot wiring](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-1/intro-to-frc-robot-wiring.html#attach-battery-connector-to-pdp)
* [ Wiring the Spark Max Controllers](https://docs.revrobotics.com/sparkmax/gs-sm)

## Go back to the top level [Readme](https://github.com/FirewallRobotics/ProgrammingSetup/blob/main/README.md#programmingsetup)

## Notes from past seasons
### VSCode
If you followed the steps above in the WPLILib Installation Guide You do not need to download Visual Studio again.

Note that while Visual Studio Code can be installed as a stand alone IDE(Integrated Development Environment) it is recommeded
to use the Visual Studio Installer linked to WPILib install. See installation steps at the following link or find the 
instructions for the corresponding competion year.
https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html

You will want to become familiar with the user interface.  Be sure to take some time to read over:  https://code.visualstudio.com/docs/getstarted/userinterface

### Install Python (co-processor programmers)

A python installation is required to do any co-processor programming.  Python 3 is required to meet our needs.
[Install Python 3](https://docs.python-guide.org/starting/installation/)
* Be sure to follow the *Python 3 Installation Guides*

#### Install VSCode Extensions

* Bracket Pair Colorizer
* CodeMetrics
* Debugger for Chrome
* Docker
* ESLint
* Git Graph
* GitLab Workflow
* GitLens
* Kubernetes
* Live Share
* Remote Development
* Todo Tree
* Trailing Semicolon
* Trailing Spaces
* Visual Studio IntelliCode
* vscode-icons
* YAML
* Python extension from Microsoft
* IntelliCode

### Install WPILib Components
* YAGSL
* WPILib-New-Commands
* ThriftyLib
* Studica
* REVLib
* ReduxLib
* photonlib
* PathplannerLib
* maplesim
* CTRE-Phoenix (All versions available)
* AdvantageKit

### Things I Wish I Knew Before Joining Programming Team:

Hello, I'm the 2025 programming captain Milo and here are a short and quite detailed list of things I wish I knew when starting out on programming team.

* The [simulator](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-simulation/index.html) is a very important part of our workflow and should be used to test if a system works or to allow us to debug and review how our code works. BUT the simulator comes with some downsides. 
	* The largest being that it fits itself around the robot, just because it works in the sim doesn't mean it will work on the real robot. 
	* The next largest being that the simulator doesn't simulate exact motor movements it will only show what data you put in(or a library like [YAGSL](https://docs.yagsl.com/) puts in).
* [Network tables](https://docs.wpilib.org/en/stable/docs/software/networktables/networktables-intro.html) are also a very large part of our workflow. anything put into network tables is archived and can be seen after the match. While outputting to the console allows you to see the direct path code takes to be executed and can get Drive Teams attention during a match. Network tables allow us to send data to our dashboard, archive for debugging, or talk with co-processors(like a raspi or the [Limelight](https://limelightvision.io/)).
* Make it simple. No matter how complicated the problem finding the easiest, and fastest solution is often the most intelligent. 
	* (EX: for the 2025 season we wanted to have a system in which the driver would press a button and the robot would go to the nearest POI(point of interest). I got into the mud finding an algorithm that would move the robot in *Just* the right way if the camera can see an [AprilTag](https://docs.wpilib.org/en/stable/docs/software/vision-processing/apriltag/apriltag-intro.html) associated with the POI. While [RoboWhales](https://www.4hwhalerobotics.org/programs/robowhales-frc-team) had dedicated buttons and tuned positions that their robot could path towards the POI.)
*  Documentation: Its important. Use of documentation be it code comments or [JavaDocs](https://www.geeksforgeeks.org/what-is-javadoc-tool-and-how-to-use-it/) is very important so that other programmers can understand what/why you are doing something. (We also post our code publicly to GitHub so having other people outside of the team understanding our code is semi-important)
* Ask for help if you can't figure a problem out. FIRST has [Coopertition®](https://www.firstinspires.org/node/20896) and people outside of the team are more than happy to help if people inside the team/AI cannot help.
	* (EX: For the 2025 season at the Wake County competition a team named Fire Hazard were having issues with their robot and one of our programmers spent the entire competition with them. The help we provided helped them to the point they did better then us in rankings.)
	* (EX: During the same season we had issues with our drive train. We asked an online forum for FRC teams and got one of the engineers that created the software behind our drive train to help us. While their help didn't fix the problem, it was fixed in an update to the drive train software and their help allowed us to quickly fix the drive train after that update)



 
