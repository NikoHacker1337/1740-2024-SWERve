# Swerve 2024 code
1740's swerve test repository for the FRC 2024 season. I am using this as a basis for the code structure of our actual 2024 codebase. 
### Robot Physical Specifications
* size w l h
* camera positions
* Swerve specifications
* general position and idea GroundIntake
* general position and idea Note Pusher

### Subsystems
#### GroundIntake
* num of NEOs
* how it works

#### Note Pusher
* num of NEOs
* how it works (is it belts or wheels)

#### Path Information
* Name: function and position

### Software Todo List (sorted by priority)
`People`
- [ ] Cordinate the software team and see who wants to help with software
- [ ] Inform software team of structure and git and PID
- [ ] Make sure they all have a solid understanding of the principles the code runs on ([see last year's repo](#last-year-repo))
- [ ] Cordinate tasks
- [ ] Assign some sort of laptop system

`General Software`
- [ ] Convert code to command robot!
- [ ] Update codebase to 2024.2 when full release is out so we aren't on version "2024.1.1-beta-2"! This involves changing: 
* Many SparkMAX declarations to Spark
* The version of the RoboRio so builds will succeed. (This is what is currently preventing update now)
- [ ] Finish readme [Robot Physical Specifications](#robot-physical-specifications)
- [ ] Consider Advantage kit and/or scope data logging for the season [Scope](https://github.com/Mechanical-Advantage/AdvantageScope) [Kit](https://github.com/Mechanical-Advantage/AdvantageKit)

`Swerve`
- [ ] Find out why turning motors were turning seemingly randomly and fix it
- [ ] Fix the one random wheel that didn't turn correctly
- [ ] Turn on field relitive control
- [ ] Add pathplanning for autos
- [ ] Finish the system functionality
- [ ] Tune the system so it works well

`Controls`
- [ ] Create a better controller scheme than last year to set up controls (addControlerFunction(func(), a)) ? (opt.)
- [ ] Create control ideas for the driver and co driver (talk to Abby and Co-Driver)
- [ ] Implement controls
- [ ] Make sure control feel is good and everything makes sense
- [ ] Controller rumble would be cool, could provide feedback on time left in match??

`Vision`
* Concurent work on limelight and lamelight
- [ ] Setup and update [limelight](https://docs.limelightvision.io/docs/docs-limelight/getting-started/summary)
- [ ] Calibrate the limelight with the online tool
- [ ] Check and fix imported limelight subsystem
- [ ] Incorperate limelight table with shuffleboard
- [ ] Get current limelight tag id and adjust co-driver controls based off it.

* Concurent work on limelight and lamelight
- [ ] Set up lamelight (Photon vision) ([see last year's repo](#last-years-repo))
- [ ] Incorperate lamelight table with shuffleboard
- [ ] Set up lamelight and calibrate it

`Note pusher`
- [ ] Figure out what this is called and rename it here
- [ ] Actually figure out what the mechanics entail and how it works
- [ ] See how the flap works
- [ ] Create stub code for testing

`Ground Intake`
- [ ] See how the ground intake works
- [ ] Create stub code
- [ ] Create subsystem

### Last Year's Repo
* :warning: This is intended as a place of reference to see the general structure, not to copy code without understanding it
* [2023 Souce Code](https://github.com/crephoto/CommandBased_2023)