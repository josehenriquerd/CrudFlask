# CrudFlask

O proposito desse código foi criar um Crud utilizando um banco de dados, Python com a biblioteca Flask e rodar ele em um docker

Ao iniciar o projeto, ele abrirá da seguinte forma:
![image](https://github.com/user-attachments/assets/68161e4e-7353-4ddd-b461-785ad4814b37)

Funcionamento de Adição:
![image](https://github.com/user-attachments/assets/2bb9de73-2c2b-47c0-90d9-29d5b02c2624)

Funcionamento de Edição:
![image](https://github.com/user-attachments/assets/02da9b50-d555-46a9-a249-2d485f55dec7)
![image](https://github.com/user-attachments/assets/8735aabd-19b9-4612-bac8-96fc640f21d6)

DockerFile:
![image](https://github.com/user-attachments/assets/3cc8bcf4-42af-4544-b539-0bca8ea5bca4)


Comandos para gerar o build e rodar o docker:

Ao baixar o repositorio, abrir o cmd e ir até o diretorio onde a pasta foi baixada, ele deve ficar:

![image](https://github.com/user-attachments/assets/8e9f0e24-3137-4f50-bb20-d7db9a160757)

Ao estar nesse diretorio, rodar:
<code>
docker build -t flaskapp .
</code>

Após rodar esse build, já pode rodar o docker:
<code>
docker run -it -p 5000:5000 flaskapp
</code>


