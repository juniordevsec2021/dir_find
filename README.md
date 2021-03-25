# dir_find
## directory bruteforcer
* This program is only for educational purposes it's a Proof Of Concept
*  Sends get request to the target url over tor network.
*  You can change it to send post request,just replace
*  response = session.get(url, allow_redirects=True)
*  with response = session.post(url, allow_redirects=True)
*  SETUP:
*  OS - linux/ubuntu distros
*  sudo apt install tor # install tor service
*  pip install requests cython # install requests and cython modules,the os module is default
*  -------------------------------------------------------------------------------------------
