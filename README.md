# To Build the Image:
# sudo docker build -t <NewImageName> .

# To Run the Container:
# sudo docker run --net=host -d -p 80:80 --name NewContainerName NewImageName
  
# To Test the Container:
# curl http://hostIpAddr
