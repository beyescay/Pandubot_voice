Steps to use this package.

1)Launch the voice_nav_commands.launch file. This launch files initialises the recognizer module and the corpus to be used.
Right now it uses navigation stack corpus.

2) Open another terminal and launch turtlebot_voice_nav.launch file. This launch file starts the node that maps the voice
commands to the robot's motion.

Now the robot should be able to move with the voice commands. Make sure the turtlebot is brought up.

3) (Optional right now) Open another terminal and launch talkback.launch. This file makes the robot to repeat
whatever the recognizer recognizes.
