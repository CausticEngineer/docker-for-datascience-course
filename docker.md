docker run -v /home/caustic/Desktop/docker:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:17aba6048f44

docker run -v /home/caustic/Desktop/docker:/home/jovyan/ -p 8888:8888 my_notebook

docker build -t my_notebook .

docker exec -it 351f9a754637 bash

docker cp wine.data e45874e02a4b:/home/jovyan/wine.data

docker-compose up
