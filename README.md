# face_recog_dlib_file dlib instalation error
 ------------------------------
 python 3.7 &
 ubuntu 16.04

 ------------------------------

 *1)* Assign root permission and update ubuntu first

 sudo su

 apt-get update


 *2)* Check your version & path for python & pip.

 which python3



 python3 -V



 which pip3



 pip3 -V


 *3)*

 pip3 install cmake


 *4)*

 apt-get install -y --fix-missing \

     build-essential \

     cmake \

     gfortran \

     git \

     wget \

     curl \

     grapgicsmagick \

     libgraphicsmagic-dev \

     libatlas-dev \

     libavcodec-dev \

     libavformat-dev \

     libgtk2.0-dev \

     libjpeg-dev \

     liblapack-dev \

     libswscale-dev \

     pkg-config \

     software-properties-common \

     zip


 *6)*

 apt-get install python3-dev


 *5)*

 pip3 install dlib


 ------------------------------

 ✅ Done
