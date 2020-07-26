# mongo-db - Simple instructions on installation (Fedora and AWS EC2)

# 1) Include mongo-db repo for FEdora

  gedit /etc/yum.repos.d/mongodb.repo
  
# 2) Add the following on the repo file

[mongodb-org-4.2]
name=MongoDB Repository
baseurl=https://repo.mongodb.org/yum/redhat/8Server/mongodb-org/4.2/x86_64/
gpgcheck=1
enabled=1
gpgkey=https://www.mongodb.org/static/pgp/server-4.2.asc

# 3) sudo yum install -y mongodb-org

# 4) More info here https://docs.mongodb.com/manual/tutorial/install-mongodb-on-red-hat (NB:- Need to tweak the repo above if installing on a AWS EC2 instance). 
