# make container
1. move to CICD Directory
2. docker build -t  imageRegistry/imagename:version .
3. Test
   docker run -it -p hostport:containerport tagimages

# deploy to kubernetes


