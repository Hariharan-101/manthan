# manthan

Q2:
clone ur repo in local machin
#  git clone <git repo link>
#  cd repo
#  vim py1.py
##############################
    print("hello world!")
################################
#  git add .
#  git commit -m "first commit"
#  git log 
  copy the latest git commit id
# git push repo url


Q3:
3 hhtp 
# vim compose.yaml
#########################
  services:
    web1:
      image: httpd
      ports:
        - "80:8081"
        
    web2:
      image: httpd
      ports:
        - "80:8082"
        
    web3:
      image: httpd
      ports:
        - "80:8083"
############################
# docker compose up 
# docker ps
# curl <localhost / ip>:8081
# curl <localhost / ip>:8082
# curl <localhost / ip>:8083

Q4:
#    docker ps 
#    docker stop <container id>
#    docker start <stopped contianer id>
