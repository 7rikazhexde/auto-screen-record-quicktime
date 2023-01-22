# Auto-Screen-Record-QuickTime
AppleScript for timed screen recording.

## Demo
![demo.gif](.demofile/demo.gif)

## Programs
#### AppleScript for on-screen screen recording
* autoScreenRecordAS.applescript
* autoScreenRecordJXA.applescript

#### AppleScript for simultaneous playback and screen recording of video files launched by QickTimePlayer
* openVideoFilesAutoPlayAndScreenRecordAS.applescript
* openVideoFilesAutoPlayAndScreenRecordJXA.applescript

## Usage
Extract and run the .applescript file stored in the program folder from the script editor.
See comments at the top of the source code for instructions on how to use the script.

If you want to run the file as an app file, please export the file format as application-specified.
Also, a security error is displayed the first time the run application is run.
In this case, please refer to the following **settings** to allow the script editor security settings.

### Setting
The script uses System Events.
To run System Events, you must allow security settings for the script editor.
In System Preferences, go to Security and Privacy > Privacy > Accessibility > Allow Computer Control for Script Editor.

## Note
#### Verified Version
macOS Monterey(version 12.4)
####  Input Record Time
Recording time depends on the process, so there will be a time gap of a few seconds to a few tens of seconds.
Please set the recording time to a value larger than the desired recording time.