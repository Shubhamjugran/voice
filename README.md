# Voicebot powered by Rasa Open Source & Botium Speech Processing 

## Tested/Implemented on below hardware :

(HP Omen Notebook 2021)  
CPU : AMD Ryzen 5 4600H (6 core 12 threads @3.0 Ghz base speed)  
RAM : 16 GB  
GPU : 6 GB (Nvidia 1660Ti)  
Nvme M.2 SSD : 500 GB  
Operating System : Windows 10 (Version : 21H1)  

## Resource Consumption :  

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&ensp;**RAM**

- (Speech To Text) kaldi STT engine &emsp;:&emsp; **3.6 GB**  
- (Text To Speech) pico TTS engine  &emsp;&nbsp;:&emsp; **2.8 GB**  
- (Frontend) GUI for test out API   &emsp;&emsp;&nbsp;:&emsp; **81.9 MB**  
- (Nginx) Web Server                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;:&emsp; **2.2 MB**  
- (Rasa Server) General Bot         &emsp;&emsp;&emsp;&emsp;&ensp;&nbsp;:&emsp; **660.6 MB**  
- (Rasa-actions-server)Email-Time   &emsp;&ensp;&nbsp;:&emsp; **51.8 MB**  



## Installation
### Software Requirements :
-> Docker : Ensure virtualization is enabled. I have installed it in WSL2 mode.[link](https://docs.docker.com/engine/install/)  
-> Python 3.7 or 3.8 (Install as per requirement of your Rasa version)  
-> IDE like pycharm,vscode etc or use old fashion cmd.  
-> Rasa Open Source [link](https://rasa.com/docs/rasa/installation)  
-> Botium Speech Processing [link](https://github.com/codeforequity-at/botium-speech-processing)  


