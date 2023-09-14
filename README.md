# Projeto Upload AI

O **Projeto Upload AI** é uma plataforma que utiliza diversas tecnologias modernas para realizar a conversão de vídeos em formato MP4 para MP3 e transcrever o conteúdo utilizando o modelo GPT-3.5 da OpenAI. Neste README, você encontrará informações sobre as tecnologias utilizadas e uma visão geral do funcionamento do projeto.

![Imagem do Projeto](https://imgur.com/zA9n0LJ.png)

## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **TypeScript**: Linguagem de programação que adiciona tipagem estática ao JavaScript, proporcionando maior robustez ao código.
- **Express**: Framework web para Node.js que facilita a criação de aplicativos web e APIs.
- **Prisma**: ORM (Object-Relational Mapping) para o Node.js que simplifica o acesso ao banco de dados e a manipulação de dados.
- **SQLite**: Banco de dados leve e eficiente, escolhido para armazenar informações relacionadas aos vídeos e transcrições.
- **React**: Biblioteca JavaScript para criação de interfaces de usuário, usada para criar a interface do projeto.
- **Tailwind CSS**: Framework CSS utilitário para agilizar o desenvolvimento do layout e estilos da aplicação.

## Funcionamento do Projeto

O projeto funciona da seguinte maneira:

1. O usuário faz o upload de um vídeo no formato MP4 para a plataforma.
2. O sistema converte o vídeo para o formato MP3.
3. A transcrição do conteúdo do vídeo é realizada utilizando o modelo GPT-3.5 da OpenAI.
4. A transcrição é armazenada no banco de dados juntamente com um prompt associado.
5. O usuário pode selecionar um prompt previamente salvo no banco de dados.
6. Com base na transcrição do vídeo e no prompt selecionado, a IA gera uma resposta.
7. A resposta gerada pela IA é disponibilizada para o usuário.

## Créditos

Este projeto é ensinado pela Rocketseat e foi desenvolvido com base em várias tecnologias modernas. Qualquer referência específica a recursos e configurações do projeto deve ser consultada no material fornecido pela Rocketseat.

Este README serve como uma visão geral do projeto e das tecnologias envolvidas, mas detalhes específicos de implementação podem ser encontrados nos recursos fornecidos pela Rocketseat.

---

Este é um projeto de exemplo que combina várias tecnologias populares para criar uma plataforma de conversão e transcrição de vídeos. Sinta-se à vontade para personalizá-lo e expandi-lo de acordo com suas necessidades específicas.
