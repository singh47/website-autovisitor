# website-autovisitor

## configure ##
Three text files need to be configured before you run the script. The files contains following data:

**agent.txt** : add browser headers in this file. **proxy.txt** : add proxy lists in format <proxy ip>:<port>. **urls.txt** : add urls you want to be visited by script, make sure to add complete url including http ot https

**agent.txt** 

Mozilla/5.0 (platform; rv:geckoversion) Gecko/geckotrail Firefox/firefoxversion

**proxy.txt** 
  
198.199.119.119:8080

67.205.174.209:3128

67.205.132.241:8080

**urls.txt** 

https://khalsalabs.com

https://khalsalabs.com/auto-website-visitor-script-in-python/



## run ##
python autovisitor.py
