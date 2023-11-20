# Aula 2 - Git / GitHub

## Como configurar, versonar e “pushar” arquivos do git para github
---
### Config iniciais:


<img src=um.png width=100 heigth=100>

    ☆ git config --global user.name “fallsmeii”

    ☆ git config -- global user.email “fallsmeii502@gmai.com”

*(use o **git config  --global edit** para editar algumas dessa configuração)* 

(***não esquecer*** de utilizar o comando ***CD*** para abrir os diretórios)

---

###  Iniciar o versionamento
✮ Crie o arquivo que dejesa versionar na pasta e ative a extensão de nomes e a exibição dos itens ocultos. Em seguida, com o botão direito, abra-o no *Git Bash*

<img src=dois.png>


    ☆ ls -l (verifica quais itens tem no diretório)

    ☆ git init (cria um novo repositório do Git)

    ☆ git status (mostra a ativação da branch master ⤵
*Branch Master é equivalente ao tronco da sua árvore, ou seja, é a parte principal do seu projeto* 

---
<img src=tres.png>

    ☆  git add . / git add “nome do arquivo”  (adiciona o arquivo ao versionamento)

    ☆  git status (permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git)

    ☆  git commit -m "descrição" 
  ☇ **O commit é um comando importantíssimo.  Ele leva as mudanças de um ambiente local para o repositório no git, permitindo ainda a inserção de uma mensagem descritiva.**
  
  ---
### Modifiquei novamente o documento ###

<img src=quatro.png>

    ☆  git status 

    ☆  git add .

    ☆  git commit -m “nova descrição”

---
    ☆ git log -u (O comando git log exibe instantâneos que receberam commit. Ele permite que você liste e
    filtre o histórico do projeto e pesquise alterações específicas)
<img src=cinco.png>

*(para sair dessa descrição detalhada é “esc : w q)*

---


### Enviando para o repositório do GitHub ###

✮ Copie e cole o link do repositório que deseja)

    ☆ git push -u origin master 
    ☆ git push 
<img src=seis.png>

---


