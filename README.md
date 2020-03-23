# Introduction
This is the api backend server that handles all incoming api requests from student-facing client. It performs CRUD application by communicating with server (MongoDB) and caching mechanism (Redis).

# Running
To start:
docker image build . -t student_api
docker container run -p 8000:8080 student_api