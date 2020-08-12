FROM python:latest

# The first parameter 'server.py' is the name of the file on the host.
# The second parameter '/server/' is the path where to put the file on the image.
# Here we put files at the image '/server/' folder
ADD server.py /server/
ADD index.html /server/

# This command changes the base directory of your image.
# Here we define '/server/' as base directory (where all commands will be executed).
WORKDIR /server/