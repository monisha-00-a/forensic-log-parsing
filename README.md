# forensic-log-parsing
A python-based command-line tool that analyzes.VLOG system session logs to detect suspicious behavior patterns.

 #  forensic log analyzer CLI tool
 ** OVERVIEW ** 
 A python-based CLI tool for :
 1. parsing ".vlog" session logs
 2. generating structured timeline
 3. detecting suspicious activity(e.g., shadow copy kill + delete)
 4. visualizing user behaviour and anomalies
 5. 
 # INPUT FORMAT 
 LOG FORMAT:
 0*1A2B[TS;1719462390]|EVNT:XR-EXEC!@KILL_USR:admin=>C:\Windows\cmd.exe

 # OUTPUT FILES
 "timeline.csv " | valid structured logs |
 "logs.csv" | invalid/ corrupted logs |
 "suspected_anomalies.csv" | anomaly detection |

 ** visualizations**
 "event_frequency.png" | event trends over time |
 "user_activity.png" | activity per user |
 "anomalies_highlighted.png" |highlighted suspicious activity |
 
