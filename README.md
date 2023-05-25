![GitHub repo size](https://img.shields.io/github/repo-size/BrenoToledo/ChatbotRelatorioTurno?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/BrenoToledo/ChatbotRelatorioTurno?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/BrenoToledo/ChatbotRelatorioTurno?style=for-the-badge)

# Chatbot Relatório Turno


Este é um BOT que desenvolvi para auxiliar na minha rotina como técnico de automação em uma fábrica. Ele me ajuda a criar um relatório diário dos problemas que ocorreram na fábrica, proporcionando uma comunicação mais rápida e padronizada com meus gestores.

### Funcionalidades Principais

- Geração automatizada de relatórios diários de problemas na fábrica.
- Registro e categorização de incidentes e falhas ocorridos.
- Notificação instantânea para os gestores sobre os problemas identificados.
- Padronização e organização das informações para uma melhor análise e tomada de decisão.


## Índice

- [Desenvolvimento](#desenvolvimento)
- [Instalação](#instalação)
- [Exemplos de Uso](#exemplos-de-uso)
- [Documentação](#documentação)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Estado do Projeto](#estado-do-projeto)
- [Contato](#contato)

## Desenvolvimento

|                     |                                                                                         |
|---------------------|-----------------------------------------------------------------------------------------|
| 🚀 Desenvolvedor       | Breno Toledo                                                                     |
| 👉 LinkedIn            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/-brenotoledo/) |
| 💻 Workspace        | ![Acer Laptop](https://img.shields.io/badge/acer%20laptop-83B81A?style=for-the-badge&logo=acer&logoColor=white)                                  |
| 💻 Sistema Operacional | ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)                                        |
| 🧭 Office              | ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)                                             |
| 🐍 Linguagens          | ![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![JSON](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white) |
| 💻 IDE                 | ![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252) ![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) |
| 💬 Chat                | ![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white) |


## Instalação



### Python

Antes de começar, você precisará ter o Python instalado em sua máquina. Se você ainda não tem o Python instalado, siga as etapas abaixo:

1. Visite o site oficial do Python em [python.org](<https://www.python.org/>) e faça o download da versão mais recente do Python.
2. Siga as instruções de instalação fornecidas para o seu sistema operacional.
3. Verifique se a instalação foi concluída com sucesso executando o seguinte comando no terminal ou prompt de comando:

   ```bash
   python --version

Isso deve exibir a versão do Python instalada.

#### Instalação das Dependências

Se o seu projeto possui um arquivo `requirements.txt` que lista as dependências, você pode instalá-las usando o seguinte comando:

```
pip install -r requirements.txt

```

Certifique-se de estar no diretório raiz do seu projeto ao executar o comando acima. Isso instalará todas as dependências listadas no arquivo `requirements.txt`.

```

Lembre-se de substituir as informações entre os colchetes `[]` com os detalhes específicos do seu projeto, como o nome do seu repositório e seu nome de usuário do GitHub.
```

### Google Colab

Se você deseja executar o repositório no Google Colab, siga as etapas abaixo:

1. Acesse [colab.research.google.com](https://colab.research.google.com/) em seu navegador.
2. Faça login na sua conta do Google.
3. Crie um novo notebook ou abra um existente.
4. Para clonar o repositório no Google Colab, execute o seguinte código em uma célula do notebook:
    
    ```
    !git clone <https://github.com/seu-usuario/seu-repositorio.git>
    
    ```
    
    Substitua `seu-usuario` pelo seu nome de usuário do GitHub e `seu-repositorio` pelo nome do seu repositório.
    
5. Navegue até o diretório do repositório usando o seguinte comando:
    
    ```
    %cd seu-repositorio
    
    ```
    
    Substitua `seu-repositorio` pelo nome do diretório do seu repositório.

## Exemplos de Uso

Forneça exemplos de uso do seu projeto. Mostre como os usuários podem aproveitar suas funcionalidades em diferentes cenários. Inclua exemplos de código e as etapas necessárias para executá-los.

## Documentação

Este é um chatbot desenvolvido para registrar ocorrências e gerar relatórios. Ele foi implementado usando a biblioteca pyTelegramBotAPI.

1. Inicie o chatbot executando o comando /new no chat do telegram.

2. Ao iniciar o chat, você será apresentado com um teclado de opções. Você pode escolher entre "Inserir ocorrência" e "Exportar Relatório".

3. Para inserir uma ocorrência, selecione a opção "Inserir ocorrência". Em seguida, siga as instruções do bot para fornecer os detalhes da ocorrência, como o problema ocorrido, o local, a existência de downtime e ordem de serviço, e o status do problema.

4. Para exportar um relatório das ocorrências registradas no dia, selecione a opção "Exportar Relatório". O bot enviará uma mensagem com o relatório formatado, incluindo a data, a equipe, a legenda e as ocorrências por local.

## Contribuição

Se você deseja contribuir para este projeto, siga as diretrizes abaixo para reportar problemas, propor melhorias e enviar solicitações de pull:

### Problemas

Se você encontrar algum problema ou bug no projeto, abra um novo *issue* no GitHub. Certifique-se de incluir informações detalhadas sobre o problema, como passos para reproduzi-lo, mensagens de erro e contexto relevante. Isso nos ajudará a entender e resolver o problema o mais rápido possível.

### Melhorias

Se você tiver sugestões de melhorias para o projeto, sinta-se à vontade para abrir um novo *issue* no GitHub. Descreva claramente sua proposta de melhoria e explique os benefícios que ela trará para o projeto. Agradecemos suas ideias e estaremos felizes em discuti-las.

### Solicitações de Pull

Se você deseja contribuir com código para o projeto, você pode enviar uma solicitação de pull. Siga as etapas abaixo para fazer isso:

1. Faça um *fork* do repositório para o seu perfil do GitHub.
2. Crie uma nova branch a partir da branch principal do projeto.
3. Faça as alterações necessárias no código em sua branch.
4. Teste suas alterações para garantir que tudo esteja funcionando corretamente.
5. Envie a solicitação de pull, descrevendo claramente as alterações que foram feitas e fornecendo informações adicionais, se necessário.
6. Aguarde o processo de revisão e discussão. Estaremos em contato para discutir e colaborar em suas alterações, se necessário.

Agradecemos antecipadamente suas contribuições para este projeto!

## Licença

Este projeto está licenciado sob a [Licença GNU General Public License v3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.en.html). Consulte o arquivo [LICENSE](link-para-arquivo-license) para obter mais informações.

A Licença GNU General Public License v3.0 (GPL-3.0) é uma licença copyleft que garante a liberdade dos usuários de executar, estudar, modificar e distribuir o software. Ela exige que qualquer software derivado seja licenciado sob os mesmos termos, garantindo que o código-fonte permaneça aberto e acessível a todos.

Ao escolher a licença GNU GPLv3, você está protegendo os direitos de liberdade do seu software, incentivando a colaboração e a contribuição da comunidade de código aberto.

Certifique-se de incluir um arquivo LICENSE em seu repositório contendo a licença completa e detalhada da GNU GPLv3. Isso ajudará a garantir que os usuários entendam os termos de uso do seu código.ue a licença que se aplica ao seu projeto e forneça um link para a licença completa, se necessário.

## Estado do Projeto

Descreva o estado atual do projeto. Você pode mencionar as funcionalidades já implementadas, o que está planejado para o futuro e como os usuários podem acompanhar as atualizações.

## Contato

Forneça informações de contato para que os usuários possam entrar em contato com você sobre o projeto. Isso pode incluir seu e-mail, perfil de mídia social ou qualquer outro meio de comunicação relevante.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/-brenotoledo/)
