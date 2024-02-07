
сбора контейнера sudo docker build -t my_container .

запуск контейнера sudo docker run -v /home/user/Desktop/data:/app/data --gpus all -p 8888:8888 my_container

сохранение образа sudo docker save -o my_container.tar my_container

sudo cp my_container.tar /media/sf_data/

загрузка образа sudo docker load -i my_container.tar