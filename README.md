# Anotacoes git e github 
 Anotações do curso Git e Git Hub do Canal do Youtube Curso em Vídeo


[Acesso à playlist no Youtube](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
    
---

## Aula 01 - O que é Git? O que é versionamento?

- Git
    - Software de Controle de Versões
- GitHub
    - Plataforma de Rede Social para Programadores
- Versionamento
    - Versões
- Modelos de versionamento:
    
    ![Untitled](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d3f3ff82-14c6-4439-bd12-7385fdeb341c/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220104T125830Z&X-Amz-Expires=86400&X-Amz-Signature=6095b8f2f8f53850fb5e30b1c34a3c6f7ca4ab6523d76590f74fa60edb492e82&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)
    
    - Modelo centralizado/linear
        - Década de 1972;
        - Necessidade de conexão constante entre máquinas e repositório central;
        - Commit para o repositório central.
    - Distribuído
        - Versionamento através de repositórios locais;
        - Repositório remoto;
        - Commit para o repositório local + push para o repositório remoto;
    - Exemplos:
        
        ![Untitled](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/828d6b5f-8672-457c-bac6-386580e0abf0/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220104%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220104T141124Z&X-Amz-Expires=86400&X-Amz-Signature=50fabaeafa820ca5c4ebc2c511cec123552c0eef24d9e3c9717dbda0f71fc06d&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D"Untitled.png"&x-id=GetObject)
        
- Principais vantagens:
    - Controle de histórico;
    - Trabalho em equipe;
    - Ramificação do projeto;
    - Segurança;
    - Organização;

---

## Aula 02 - O que é GitHub? Para que ele serve?

### Características

---

- Repositórios ilimitados;
- Hospedagem de código-fonte
- Características de rede social
    - Networking
- GitHub Pages Integrado
- Colaboração
- Forks ⇒ Continuar projetos por conta própria

### Outras opções de repositórios remotos

---

- Gitlab
- BitBucket
- Phabricator
- Gogs
- Kallithea

---

## Aula 03 - A Evolução do Git e GitHub

- 1985
    - **CVS**
    - Centralizado
    - Open Source
    - Mais popular
    - Alguns problemas:
        - Commit de 4 minutos
        - Não permitia a renomeação dos arquivos
- 2000
    - **SVN** - Subversion
    - Centralizado
    - Open Source
    - CVS - like ⇒ Queria copiar muito o CVS, tentando corrigir alguns problemas
- 2000 - Distribuído
    - **BitKeeper** - McAvoy
    - Distribuído
    - Proprietário
    - Versão Comunidade
    - CVS-Free
    - Kernel do linux
- 2004
    - **SourcePuller**
    - Engenharia Reversa
    - Recursos destravados do BitKeeper para a comunidade
- 2005
    - **Bitkeeper**
    - Nova licença
    - Acesso a metadados limitado
    - Acesso aos arquivos versionados apenas na versão comercial
- 2005
    - **Git**
    - Distribuído
    - Open Source
    - Feito em 10 dias (uma versão usável)
    - Performance - segundos
    - Criado pelo criador do Linux

---

### O que quer dizer Git? - Segundo o Linus torvalds

- Três letras do alfabeto - palavra simples para comandos e que não existia em outras linguagens.
- Gíria para Teimoso, cabeça-dura, pensa que sempre está certo - como uma auto-homenagem
- Global information tracker - Quando funciona
- Goddamn idiotic truckload of sh#t - Quando não funciona

---

### GitHub

- 2008
- 4 Amigos
- Proprietário
- Baseado em Git
- Crescimento meteórico
    - 2009: 46k repositórios
    - 2010: 100k usuários/ 1M respositórios
    - 2011: Ultrapassou SourceForce
    - 2013: 3M usuários / 5M repositórios
    - 2016: 14º lugar na lista da Forbes
    - 2018:  Maior ataque de DDoS da história
        - Praticamente derrubou a internet
        - 1,35 TB/s
    - 2018: Comprado pela Microsoft por 7.5 bilhões de dólares
- Operação independente
- 2020: Github compra a NPM (Node Package Manager)
    - NPM: Maior gestor de pacotes de JS do mundo

---

## Aula 04 - Instalações e configurações importantes

Aula Prática. 

- Instalação do Google Chrome sugerida, mas não realizada
- Git - OK
- GitHub Desktop - Ok

---

## Aula 05 - Criando o primeiro Repositório

- Aula prática
- Utilizando o GitHub Desktop sincronizado com o Git e o Visual Studio Code

---

## Aula 06 - Instalando GitHub Desktop no Linux

- Aula prática não aplicada, já que utilizo o Sistema Operacional Windows

---

## Aula 07 - Clonando um repositório

- Aula Prática
- Sempre que iniciar um dia de trabalho:
    - Utilizar a função Fetch Origin
    - Fetch origin ⇒ Verifica se as versões da máquina e do repositório local estão iguais

---

## Aula 08 - Versionando seus projetos antigos

- Aula prática
- Nessa aula é apresentado como pode-se de versionar repositórios com projetos antigos.
- Sugestão: deixar os repositórios públicos, para compartilhamento com a comunidade

---

## Aula 09 - Você sabe usar Issues?

- Issues ⇒ Problema.
    - Utilizada quando não se sabe o que houve de errado com um programa, e avisa-se aos desenvolvedores.
- Pull request ⇒ Push para branch secundária
    - Ao encontrar um erro em um determinado código, é possível realizar o fork, cria-se uma branch secundária, faz-se melhorias e correção de erros e depois abre-se um pull request. Se o proprietário aprovar, a alteração fica na branch principal
- Sempre pesquisar os erros e só depois criar uma issue
- O Git tem suporte para assinaturas padrão

---

## Aula 10 - Guia de Linguagem Markdown

- Manual de Markdown
    
    [Acesso ao Manual em pdf](https://github.com/gustavoguanabara/git-github/blob/master/manuais-PDF/guia-markdown.pdf)
    
- Sugestão de livro para estudo de Git
    - Git Pro
    - Conhecendo o Git:
        - Git e GitHub com comandos
- GitHub é compatível com MarkDown

### Markdown

---

- Linguagem de marcação
- Alta facilidade de leitura, mesmo sem a formatação
- Utilizada principalmente em três áreas do GitHub:
    - README
    - Issues
    - Pull requestes

### Destaques de texto

- **Negrito**
    - Texto entre ** 
    - Texto entre __
- *Itálico*
    - Texto entre *
    - Texto entre _
- ~~Riscado~~
    - ~~
    - ~
- __*Mistura - Negrito e itálico*__
    - __*
- ´Código em uma linha´
    - ` (crases)
    - Obs.: Fonte destaque
- '''Código:''' (crases)
     ``` 
    Código
    Outra linha de código
    ```
    

### Títulos

# H1 (#Título1)
    
    
## H2 (##Título2)
    
    
### H3  (###Título3)
    
    

### Linhas
---
***

/***

/—- (Sem a barra)

### Listas

- Listas Numeradas:
    
    1.Texto (1. Texto)
    
    42. Texto (42. Texto)
    
    - Para que se tenha uma lista aninhada, basta utilizar 3 espaços
    1. Lista Aninhada
    
       1. Lista Aninhada 2 (1. Lista Aninhada.)
    
- Listas demarcadas:
    - Usa-se os símbolos * ou -:
        
        / *Texto (Sem a barra)
        
        / - Texto 
        
- Lista de Tarefas
    - [ ] Tarefa 1 (A ser realizada) - [ ]
    - [x] Tarefa 2 (Concluída) - [x]

### Imagens e links

- Sugestão: Imagens de 400 a 500 píxels de tamanho no máximo
- Para adicionar as imagens, basta arrastar a imagem de uma pasta local para a caixa de texto do GitHub
- Formato:
    - [Descrição da imagem] (Link da imagem)
- Links:
    - [Texto que será apresentado] (URL)

### Tabela

- Usa-se o símbolo |
- Exemplo:
    
    >Num | Nome | Nota 
    >1 | Gustavo | 8,5
    >2 | José | 9,0

Vai se tornar:

Num | Nome | Nota
:---: | :---: | :---:
1| Gustavo | 8,5
2| José |10
3| Maria | 9,5
    

### Emojis

- : nome_do_emoji
- Repositório com o nome dos emojis:
    - https://github.com/ikatyang/emoji-cheat-sheet
- Obs.: Os emoji não funcionam como títulos das issues
- Os da EmojiPedia funcionam:
    - [https://emojipedia.org](https://emojipedia.org/)

### Citações e marcações
- Citações (Diretas) (Usando o símbolo de maior >)
    >Texto da citação
    >Texto da citação
- Marcações
    - @
>Resposta (Quote Reply)
    
    /> (Sem a barra)
    - Para responder a um comentário específico, basta clicar no canto superior direito do comentário, ir nas reticências, e clicar em quote reply
    - Save Reply

---

## Aula 11 - Seu GitHub muito mais seguro

- Git - Segurança local
- GitHub - sugestões para uma senha segura:
    - Pelo menos 8 características
    - Letras e números
    - Maiúsculas e minúsculas
    - Símbolos
    - Evitar nomes e palavras comuns
    - Evitar padrões
    - Nunca compartilhar uma senha
- Parte prática: configuração da verificação em duas etapas do GitHub utilizando o Google Authentificator

---

## Aula 12 - Git Branches de forma fácil e com exemplo

### Branchs

- Git ⇒ Trabalha com grafos
- Master(Repositório local) ⇒ Origin(Repositório remoto)
- Criação de novas ramificações para evitar problemas na branch principal
- Merge ⇒ Junção da feature secundária com a branch master
- Resolução de conflitos ⇒ Caso haja conflitos entre os itens da branch, é possível compará-las e manter uma das versões, ou até as duas versões

---

## Aula 13 - Hospedagem Grátis no GitHub Pages

- Depois de um Push, demora de 30s a 1 min para a página funcionar normalmente

---