```
  ░██████                                                      
 ░██   ░██                                                     
░██        ░████████  ░███████ ░██░████░███████                
 ░████████ ░██    ░██░██    ░██░███   ░██    ░██               
        ░██░██    ░██░██    ░██░██    ░█████████               
 ░██   ░██ ░██    ░██░██    ░██░██    ░██                      
  ░██████  ░██    ░██ ░███████ ░██     ░███████                

░███     ░███                    ░██   ░██                     
░████   ░████                          ░██                     
░██░██ ░██░██ ░███████ ░████████ ░██░████████░███████ ░██░████ 
░██ ░████ ░██░██    ░██░██    ░██░██   ░██  ░██    ░██░███     
░██  ░██  ░██░██    ░██░██    ░██░██   ░██  ░██    ░██░██      
░██       ░██░██    ░██░██    ░██░██   ░██  ░██    ░██░██      
░██       ░██ ░███████ ░██    ░██░██    ░████░███████ ░██      
                                                               
                                                               
                                                               
```

Because you need to know just how bad you are snoring and self-diagnose using more AI - all the money and power to tech bros



Snore Monitor is a vibe coded portable Windows application for recording and reviewing overnight breathing and possible snoring activity.

It continuously records lossless mono audio in crash-resistant chunks while analyzing microphone loudness and spectral characteristics locally. After recording, users can review the complete session through an interactive timeline, identify possible-snoring periods, inspect estimated dBFS levels and spectrograms, and begin playback from any selected time.

Features include:

- Continuous lossless overnight audio recording
- Possible-snoring detection and timestamps
- Full-session average and peak loudness graph
- Click-anywhere timeline playback
- Estimated average and peak dBFS during playback
- Time-synchronized spectrogram with dBFS color scale
- Autosave checkpoints and partial-recording recovery
- Plain-text logs and CSV loudness history
- Portable Windows 10/11 build with no Python installation required
- Fully local processing with no cloud services or accounts

Snore Monitor is an experimental sound-analysis tool and is not a medical device or a substitute for professional sleep assessment.

The portable Windows app saves all recordings here:
C:\Users\<your-Windows-name>\AppData\Local\SnoreMonitor\logs
On your computer, that should be:
C:\Users\raymo\AppData\Local\SnoreMonitor\logs
Inside:
- snore_log_...txt — session details and detected snoring periods
- snore_log_..._levels.csv — full-session loudness history
- audio\snore_log_... — lossless FLAC audio chunks for that session
The easiest way to reach it is the Open logs button in the Record tab.
