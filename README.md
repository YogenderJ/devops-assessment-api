docker build -t tech-sonar-api -f Dockerfile .


docker run -d -p 80:5050 tech-sonar-api

