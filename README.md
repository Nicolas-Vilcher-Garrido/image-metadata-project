Projeto de Extração de Metadados de Imagens

Descrição:

Este projeto tem como objetivo a criação de um gerenciador de imagens de drones que extrai e armazena metadados de imagens capturadas. Utilizando Python, a aplicação permite que usuários selecionem imagens e, automaticamente, extraiam informações relevantes como data de captura, localização GPS, tamanho da imagem, entre outros dados. Os metadados são armazenados em um banco de dados SQL Server, proporcionando uma forma estruturada de manter as informações.

Funcionalidades
Seleção de Imagens: O usuário pode selecionar arquivos de imagem no formato JPG, JPEG e PNG diretamente pela interface gráfica.
Extração Automática de Metadados: Ao selecionar uma imagem, os metadados são extraídos automaticamente utilizando a biblioteca PIL para manipulação de imagens e piexif para leitura de informações EXIF.
Armazenamento em Banco de Dados: Os dados extraídos são salvos em um banco de dados SQL Server, permitindo fácil consulta e gerenciamento das informações.
Interface Gráfica Intuitiva: A aplicação possui uma interface simples e amigável, facilitando o uso mesmo para usuários com pouca experiência técnica.
Tecnologias Utilizadas
Python: Linguagem de programação utilizada para o desenvolvimento da aplicação.
PIL (Pillow): Biblioteca para manipulação de imagens.
piexif: Biblioteca para leitura e escrita de metadados EXIF.
SQLite: Sistema de gerenciamento de banco de dados utilizado para armazenar os metadados.
