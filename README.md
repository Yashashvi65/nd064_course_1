# nd064_C1
Run flask app using docker :
</br>
1.docker build -t python-helloworld .
</br>
2.docker images(to have a a look at the images created)
</br>
3.docker run -d -p 5000:5000 python-helloworld (run docker app locally)
</br>
4. docker ps(to see running containers)
</br>
5. docker tag python-helloworld yashashvi65/python-helloworld(docker repo):v1.0.0
</br>
6. docker images (to see images)
</br>
7. docker push yashashvi65/python-helloworld:v1.0.0 
</br>
8. docker login (if logged out)
