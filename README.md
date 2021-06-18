# nd064_C1
Run flask app using docker -
1.docker build -t python-helloworld .
2.docker images(to have a a look at the images created)
3.docker run -d -p 5000:5000 python-helloworld (run docker app locally)
4. docker ps(to see running containers)
5. docker tag python-helloworld yashashvi65/python-helloworld(docker repo):v1.0.0
6. docker images (to see images)
7. docker push yashashvi65/python-helloworld:v1.0.0 
8. docker login (if logged out)
