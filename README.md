# Aula 2 - Git / GitHub

## Como configurar, versonar e “pushar” arquivos do git para github
---
### Config iniciais:


<img src="https://github.com/fallsmeii/Aula-2/assets/149728744/b8fc6d7b-d27f-4f47-8126-c91863f70f60" width="700px" />   
</div>



    ☆ git config --global user.name “fallsmeii”

    ☆ git config -- global user.email “fallsmeii502@gmai.com”

*(use o **git config  --global edit** para editar algumas dessa configuração)* 

(***não esquecer*** de utilizar o comando ***CD*** para abrir os diretórios)

---

###  Iniciar o versionamento
✮ Crie o arquivo que dejesa versionar na pasta e ative a extensão de nomes e a exibição dos itens ocultos. Em seguida, com o botão direito, abra-o no *Git Bash*

<img src="https://github.com/fallsmeii/Aula-2/assets/149728744/d41443f6-45b3-4311-b384-86d30f50249d" width="700px" />   
</div>


    ☆ ls -l (verifica quais itens tem no diretório)

    ☆ git init (cria um novo repositório do Git)

    ☆ git status (mostra a ativação da branch master ⤵
*Branch Master é equivalente ao tronco da sua árvore, ou seja, é a parte principal do seu projeto* 

---
<img src="https://github.com/fallsmeii/Aula-2/assets/149728744/a4468908-8bd0-4236-baca-8f413fbe0783" width="700px" />   
</div>

    ☆  git add . / git add “nome do arquivo”  (adiciona o arquivo ao versionamento)

    ☆  git status (permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git)

    ☆  git commit -m "descrição" 
  ☇ **O commit é um comando importantíssimo.  Ele leva as mudanças de um ambiente local para o repositório no git, permitindo ainda a inserção de uma mensagem descritiva.**
  
  ---
### Modifiquei novamente o documento ###

<img src="https://github.com/fallsmeii/Aula-2/assets/149728744/98c30a34-dc49-488e-9b4e-5a7b47d5a7c6" width="700px" />   
</div>

    ☆  git status 

    ☆  git add .

    ☆  git commit -m “nova descrição”

---
    ☆ git log -u (O comando git log exibe instantâneos que receberam commit. Ele permite que você liste e
    filtre o histórico do projeto e pesquise alterações específicas)
<img src="https://github.com/fallsmeii/Aula-2/assets/149728744/58592cf8-28a6-439d-a4d3-c0a496dca3f4" width="700px" />   
</div>


*(para sair dessa descrição detalhada é “esc : w q)*

---


### Enviando para o repositório do GitHub ###

✮ Copie e cole o link do repositório que deseja)

    ☆ git push -u origin master 
    ☆ git push 
<img src="https://github.com/fallsmeii/Aula-2/assets/149728744/2eb3bb72-03b7-4c22-be68-8754cc21e88f" width="700px" />   
</div>

---
---
---

### Anotações da Aula ###
    ☆ git versiona o cods e é publi no hub
    ☆ ~ = sempre indica usuario
    ☆ pwd qual diretorio atual
    ☆ cd muda p diret
    ☆ inset - edita
    ☆ sair do edit esq dois pontos wq
    ☆ git n versiona sem o user_usuario e user_email
    ☆ commit confirma o versionamento
    ☆ git add. (tudo pra versionar)
    ☆ unstage - tira do versionamento
    ☆ git commit -m mensagem pra ve o q foi feito
    ☆ git add e git commit é obrigatório
    ☆ git log -u tds as alterações
    ☆ ctrl c = volta pra linha de comando
    ☆ ls -l lx
    ☆ ls ww
    ☆ ctrl l - clear no win10
    p
