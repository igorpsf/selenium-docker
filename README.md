# SeleniumWebdriverWithDocker

### Project URL's: 
1) http://newtours.demoaut.com
2) https://duckduckgo.com

### Chrome Driver: 
1) https://chromedriver.chromium.org/downloads

### Maven dependencies: https://mvnrepository.com
1) Selenium Java » 3.141.59
2) TestNG » 6.14.3

### Docker:
1) docker pull selenium/hub:3.14
2) docker pull selenium/node-firefox:3.14
3) docker pull selenium/node-chrome:3.14 

### Zalenium
1) https://opensource.zalando.com/zalenium/

##### Pull docker-selenium
    docker pull elgalu/selenium

##### Run it!
    docker run --rm -ti --name zalenium -p 4444:4444 \
      -v /var/run/docker.sock:/var/run/docker.sock \
      -v /tmp/videos:/home/seluser/videos \
      --privileged dosel/zalenium start
      
http://localhost:4444/grid/console
http://localhost:4444/dashboard/

### Original
1) https://github.com/vinsguru/selenium-docker


##OPTIONAL 
##### Pull Zalenium
    docker pull dosel/zalenium