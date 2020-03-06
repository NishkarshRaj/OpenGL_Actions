FROM ubuntu
RUN apt-get -y update
RUN apt-get -y install apt-utils
RUN apt-get -y install g++
RUN apt-get -y install freeglut3-dev
ADD script1.sh /script1.sh
ADD src.cpp /Hut.cpp
RUN chmod +x /script1.sh
CMD /script1.sh
