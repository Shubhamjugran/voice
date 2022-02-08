# Voicebot powered by Rasa Open Source & Botium Speech Processing :robot:  :sound:

## Tested/Implemented on below hardware ::abacus:

(HP Omen Notebook 2021)  
CPU : AMD Ryzen 5 4600H (6 core 12 threads @3.0 Ghz base speed)  
RAM : 16 GB  
GPU : 6 GB (Nvidia 1660Ti)  
Nvme M.2 SSD : 500 GB  
Operating System : Windows 10 (Version : 21H1)  

## Installation :writing_hand:  
### Software Requirements ::point_down:
-> Docker : Ensure virtualization is enabled. I have installed it in WSL2 mode.[link](https://docs.docker.com/engine/install/)  
-> Python 3.7 or 3.8 (Install as per requirement of your Rasa version)  
-> IDE like pycharm,vscode etc or cmd.  
-> Rasa Open Source [link](https://rasa.com/docs/rasa/installation)  
-> Botium Speech Processing [link](https://github.com/codeforequity-at/botium-speech-processing)
-> Webpage for chatbot interaction.

## Resource Consumption (Idle) :hourglass_flowing_sand:  

- (Speech To Text) kaldi STT engine  ![This is an image](/screenshots/kaldi.png)
- (Text To Speech) pico TTS engine   ![This is an image](/screenshots/tts.png)
- (Frontend) GUI for test out API    ![This is an image](/screenshots/frntend.png)
- (Nginx) Web Server                 ![This is an image](/screenshots/nginx.png)
- (Rasa Server) General Bot          ![This is an image](/screenshots/rasa.png)
- (Rasa-actions-server)              ![This is an image](/screenshots/actions.png)
- (Duckling-server)                  ![This is an image](/screenshots/duckling.png)

### Okteto Endpoints :link:  

- Rasa Server [link](https://rasa-server-rasa281-shubhamjugran.cloud.okteto.net)
- Duckling Server [link](https://duckling-server-rasa281-shubhamjugran.cloud.okteto.net)

  

## Achievements ::medal_sports:
- Found a bug while deploying botium speech processing on Okteto  ![This is an image](/screenshots/mail.png)
- Contributed docker-logs to okteto [link](https://github.com/okteto/okteto/issues/2119)
- logs [link](https://github.com/Shubhamjugran/voice/tree/main/logs)  
