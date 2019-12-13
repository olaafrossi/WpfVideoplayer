# Fullscreen videoplayer controlable through http requests
This app uses mediaelement in WPF 

Videos should be placed in the /videos folder
The webserver will start on port 8080

#### Get current status
http://localhost:8080/status

#### Start video a.mp4 with loop enabled
http://localhost:8080/start/a.mp4/?loop=1

#### Start video b.mp4 without loop
http://localhost:8080/start/b.mp4

####If playing stop.
http://localhost:8080/stop

#### Flip video
Add &flipX=1 or flipY=1 to flip the video over x or y axis
