# Build 
    docker-compose up --build

# Database
   http://localhost:8080/
   User/Pass: root/root
   Add Database : company
   Add table : users(id,name)

# Run 
    http://localhost:8000/

 
# Refer :
    https://github.com/trungnt89/lumen_app
    https://yossiabramov.com/blog/setting-up-lumen-and-mysql-with-docker-part-i
    https://yossiabramov.com/blog/setting-up-lumen-and-mysql-with-docker-part-ii

# Remove
    docker rm -vf $(docker ps -aq);
    docker rmi -f $(docker images -aq);
    docker volume rm $(docker volume ls -q)

