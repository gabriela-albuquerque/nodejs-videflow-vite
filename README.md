# VidFlow utilizando o Vite

O VidFlow é uma plataforma de vídeos de tecnologia, que permite aos usuários navegar por categorias e buscar vídeos por meio de uma barra de pesquisa. O projeto foi originalmente desenvolvido durante a formação em JS da Alura, onde criei a base da aplicação e implementei funcionalidades essenciais.

## Problemas na Versão Anterior

Na versão anterior, após fazer o deploy na Vercel, os vídeos não podiam ser acessados já que seus arquivos estavam armazenados localmente no servidor de desenvolvimento.

## Melhorias com o Vite

Neste upgrade do projeto, o objetivo foi tornar a aplicação totalmente funcional e acessível a todos.

Isso foi implementado com o uso das variáveis de ambiente do **Vite**, especialmente import.meta.env.PROD, foi possível criar um servidor de pré-produção e a aplicação pode ser implantada na Vercel com os vídeos disponíveis diretamente via URL.