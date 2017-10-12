docker-arachni
========

http://www.arachni-scanner.com/

**Docker image with arachni**


**arachni cli**  
docker run -ti --rm bios/docker-arachni arachni http://target  
https://github.com/Arachni/arachni/wiki/Command-line-user-interface  

**arachni web**  
docker run -d --name arachni_web -p 9292:9292 --rm bios/docker-arachni arachni_web -o 0.0.0.0  
https://github.com/Arachni/arachni-ui-web/wiki  


