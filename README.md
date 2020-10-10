# ft_server

Step 1:

docker build -t <NomImage> .


Step 2:

docker run -d -p 80:80 -p 443:443 <NomImage>

Step 3:

docker-machine ip

copy your ip into your browser