Script de Clonagem de Site

Este script em bash automatiza o processo de clonagem de um site usando o Puppeteer e o Website Scraper.
Requisitos

    Node.js
    npm
    Google Chrome (ou Chromium)
    Acesso sudo (para instalar pacotes npm globalmente e criar diretórios)

    Funcionamento

O script realiza as seguintes etapas:

    Criação de Diretórios: Verifica se os diretórios necessários (puppeteer e projeto) existem. Se não existirem, os diretórios serão criados.

    Concessão de Permissões: Concede permissões de leitura, escrita e execução aos diretórios puppeteer e projeto.

    Baixar Arquivos Necessários: Entra no diretório do projeto, verifica se ele existe e baixa os pacotes npm necessários (website-scraper e website-scraper-puppeteer) usando o comando npm.

    Clonagem do Site: Copia o arquivo index.js para o diretório do projeto e executa o arquivo index.js usando o Node.js para clonar o site.

Personalização

Você pode personalizar o script ajustando os caminhos dos diretórios e arquivos conforme necessário, bem como adicionando ou removendo etapas do processo de clonagem do site.
Notas

    Certifique-se de ter o Google Chrome (ou Chromium) instalado e definir a variável de ambiente PUPPETEER_EXECUTABLE_PATH apontando para o executável do navegador.

