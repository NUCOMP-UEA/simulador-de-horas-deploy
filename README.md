<p align="center">
    <a href="https://www2.uea.edu.br" target="blank"><img hspace="25" src="assets/logo_uea.svg" width="200" alt="Logo UEA"/></a>
    <a target="_blank"><img hspace="25" src="assets/nucomp.png" width="200" alt="Logo NUCOMP" /></a>
</p>

<h1 align="center"> Descrição do Projeto </h1>

<p align="center">Simulador de horas complementares para o site do curso de Engenharia de Computação, Sistemas de Informação e Licenciatura em Computação.</p>

<h2 align="center"> Tecnologias Utilizadas </h2>

<p align="center">
	<a href="https://www.python.org"><img alt="Static Badge" src="https://img.shields.io/badge/python-white?style=for-the-badge&logo=python"></a>
	<a href="https://fastapi.tiangolo.com"><img alt="Static Badge" src="https://img.shields.io/badge/fastapi-white?style=for-the-badge&logo=FastAPI"></a>
	<a href="https://www.mongodb.com/pt-br"><img alt="Static Badge" src="https://img.shields.io/badge/mongodb-white?style=for-the-badge&logo=MongoDB"></a>
	<a href="https://www.docker.com"><img alt="Static Badge" src="https://img.shields.io/badge/Docker-white?style=for-the-badge&logo=docker&logoColor=%232496ED"></a>
	<a href="https://python-poetry.org"><img alt="Static Badge" src="https://img.shields.io/badge/poetry-white?style=for-the-badge&logo=Poetry"></a>
</p>

### Pré-requisito:

* Será necessário criar a imagem da API utilizando o Docker;

* O repositório com o Dockerfile (necessário para criar a imagem da API) poderá ser encontrado no seguinte link:
    * <a href="https://github.com/NUCOMP-UEA/Simulador-de-horas-API">API do Simulador de Horas;</a>
    * O Dockerfile estará na branch **feat/activity-crud**, na **raiz do projeto**.

### Execução do comando no terminal para subir a imagem da API

```zsh
docker compose up -d && docker logs add_hours_api -f
```