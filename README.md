1. Download the script file
2. chmod +x autofan.sh
3. Modify the TARGET_TEMP, MIN_FAN, MAX_FAN, CRITICAL_TEMP, CRITICAL_ACTION if needed
4. mv autofan.sh /usr/sbin/autofan

Then you can run autofan everywhere~




If you do not have py-nvtools, you shoud deploy it first:
wget https://github.com/Akisoft41/py-nvtool/releases/download/v0.2.0/py-nvtool.py
chmod +x py-nvtool.py
mv py-nvtool.py /usr/sbin/py-nvtool
