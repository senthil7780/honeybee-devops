# Please execute the following command to run
docker build . -t senthil7780/challenge1:latest

#To run the docker file, please execute the below

docker run -ti senthil7780/challenge1:latest /bin/bash -c "python access_github_details.py; ls -lrta; sh"

#The repos input  need to be break by pressing Ctrl+D twice