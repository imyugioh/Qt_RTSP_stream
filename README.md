# IP Freely (IP/Web camera stream viewer and recorder)

## Background

I started this project shortly after buying and installing some RTSP compatible IP security cameras at my house. The software that came with the cameras was adequate but not great; relying on ActiveX and Internet Explorer. Instead this project provides a native application to view and record up to 4 cameras' streams. Currently, this application does not give you any control over the IP cameras' on-board settings.

## Key Features (Current Version 1.2.0.0)

- Clean and intuitive UI, hopefully!
- Multi-threaded.
- Cross-platform (Windows and Linux).
- Supports up to 4 user configurable IP or web camera streams displayed in a 2x2 grid.
- If a suitable URL is provided then you can view a camera's on-board storage (e.g. SD card) and download the content to your PC.
- The user can view a larger expanded view from any of the 4 streams.
- Still snapshot images can be taken from the camera feeds at any time with the click of a button.
- Local AVI (DivX on Windows, XDiv on Linux) video recordings can be made from the camera streams at the click of button.
- Scheduled recording can be setup and enabled on a per camera basis, with the schedule allowing selection of days and active hours in the day.
- Motion detection can be setup with user-configurable scheduling (similar to scheduled recordings).
- Per camera user definable motion detection regions.
- Per camera motion detection algorithm sensitivity (off, low sensitivity, medium sensitivity, high sensitivity and manual settings).
- Built-in disk space manager. User can configure how many days recordings to keep and a maximum percentage of used disk space. The disk manager periodically i nthe background will remove oldest data first and ensures used space always falls within defined limits.
- (Planned) Motion triggered email send email alerts.
- (Planned) Built-in web server to display some basic features, such as periodically updated snapshots from the camera feeds.

## Screen-shots

### Preferences

![alt text][pic04]

![alt text][pic05]

![alt text][pic08]

### Camera Setup

![alt text][pic03]

### Main Screen

![alt text][pic01]

![alt text][pic09]

![alt text][pic02]

![alt text][pic06]

![alt text][pic07]

[pic01]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic01.png "Main screen displaying one camera."
[pic02]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic02.png "Expanded view of camera 1's feed."
[pic03]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic03.png "Camera setup dialog."
[pic04]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic04.png "General preferences."
[pic05]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic05.png "Recording schedule preferences."
[pic06]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic06.png "Camera storage browser."
[pic07]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic07.png "Camera stream recording."
[pic08]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic08.png "Motion detection schedule."
[pic09]: https://github.com/dac1976/IP-Freely/blob/master/Images/pic09.png "Motion region setup."
