1. Install docker in the machine (If Mac docker desktop)
2. Clone the project.  
3. Set .env as needed.  
4. Run below commands:  
```bash
docker-compose build --no-cache
docker-compose up -d
```
5. Start you development now all good now. no need to setup anything.
6. You can See your project on URL: http://localhost:8000
7. To stop server use below command
```bash
docker-compose down --volumes  
```
(Can Use this without --volumes also if not need to remove volumes)

YOU CAN USE BELOW FILES IN ANY LARAVEL PROJECT (MAKE SURE TO CHECK THE RELAVANT PHP AND LARAVEL VERSIONS)

docker-compose.yml  
Dockerfile  
000-default.conf  
