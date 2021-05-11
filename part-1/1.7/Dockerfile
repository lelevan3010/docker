FROM ubuntu:16.04 
 
WORKDIR /mydir

COPY script.sh .

RUN apt-get update && apt-get install sudo -y && apt-get install curl -y
RUN chmod +x ./script.sh

CMD ["/bin/bash"]
