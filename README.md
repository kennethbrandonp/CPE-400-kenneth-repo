# How to Run SpyOT application
Project Setup
First you want the libraries we'll be using so plug this command into ther terminal:
```sh
pip install -r requirements.txt
```
In the folder labeled "main" is the packaged form of SpyOT. The executable 'main.exe' should be able to run after pip installing the requirements.

*If for some reason the executable package doesn't work:

In the repo, open main.py in your IDE and in the upper right corner hit "run" main.py is open. That should run the application.

## Path Handling
Make sure you have both Wireshark and Nmap downloaded:
```sh
Wireshark download: https://www.wireshark.org/download.html
Nmap download: https://nmap.org/download
```
If you continue to have problems with these libraries, make sure their path's are set in the environment variables on your local computer:
```sh
  Go to your start menu and type: "Edit environment variables for your account"
  Go to: Path -> Edit -> Browse -> Program(x86) 
  Choose folders for either Wireshark or Nmap (Depending on which one you're setting the path for)
  Click "OK" until you're closed out of all "Edit environment variables for your account" windows.
```
Beyond this, there is no other troubleshooting that needs to be done. The application should run. If it does not, refer to the CPE 400 Project Report on Details and results for an example of it running:
```sh
Project report: https://docs.google.com/document/d/1khIZ1bJKohxXY2bAndTMmbEtwAzdih82Pmici_VJiCg/edit?usp=sharing# 
```
