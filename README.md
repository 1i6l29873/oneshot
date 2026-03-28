1.pkg update && pkg install tsu python root-repo wpa-supplicant -y && pip install wcwidth

  (pkg install -y git tsu python wpa-supplicant pixiewps iw openssl)
  
2.curl -O https://raw.githubusercontent.com/1i6l29873/oneshot/refs/heads/main/oneshot1.py

3.tsu -s "python oneshot1.py -i wlan0 -B"
