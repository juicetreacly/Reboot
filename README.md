# PC Reboot Script
# Overview
This repository contains a simple batch file that is used to reboot a Windows PC. The script uses the built-in shutdown command in Windows to initiate a reboot. This can be useful for automating system restarts or scheduling reboots in specific scenarios.

# How It Works
The batch file includes the following command:

# batch
Copy code
shutdown /r
shutdown: This is the Windows command used to shut down, restart, or log off the computer.
/r: This option tells the system to restart after shutdown. Without this option, the system would simply shut down.
# Usage
To use the batch file:

Download the file or copy the script.
Run the batch file by double-clicking it, or execute it via the Command Prompt:
Open the Command Prompt (press Win + R, type cmd, and press Enter).
Navigate to the directory where the batch file is located.
Run the file by typing its name and pressing Enter.
The system will initiate a restart process.

# Additional Notes
Make sure you have saved your work before running this script, as it will restart the computer immediately.
You can modify this script to include a delay before the restart. For example, adding the /t option with a number of seconds:
# batch
Copy code
shutdown /r /t 60
This will delay the restart by 60 seconds.
# License
This script is open-source, and you are free to modify and distribute it. Refer to the repository's license for more details.
# Disclaimer
This is for educational purposes only
