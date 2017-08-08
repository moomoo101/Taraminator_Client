# Taraminator_Client
This repo contains the client application for the Taraminator project, which is used to collect and display points from the server.
## Instructions
### Prerequisites
* Ubuntu 14.04
* OpenCV Installed
* PCL Installed
### To compile
1. Clone the repository using following command (replace [url] with actual repository url):

git clone [url]
2. Navigate to "build" folder

cd build
3. Use following commands to compile:

cmake ..
sudo make
### To run client application
sudo ./client_viewer [host_ip] [port]

Note: Replace host_ip with the ip address of the client. Port number should be 8080.
