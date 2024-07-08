Helloworld Servlet example with corresponding Dockerfile

Use maven Build first to create war file in the Target folder.

mvn clean package

docker run -d -p 8080:8080 --name mavenbuild mavenbuild
