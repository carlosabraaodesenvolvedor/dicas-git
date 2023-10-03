# Comandos uteis do GIT HUB




## Comando para criar um novo repositorio
### linha de comando

```
echo "# teste" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/carlosabraaodesenvolvedor/teste.git
git push -u origin main

```
## Para enviar um repositório existente 
### linha de comando
```
git remote add origin https://github.com/carlosabraaodesenvolvedor/teste.git
git branch -M main
git push -u origin main

```
# Varios Comandos do GIT e exemplos de uso

* init : inicializar o projeto/ repositório
* branch : informações sobre branches
* checkout : navegar pelas branches 
* status : checar o que há de novo / mudanças
* clone : baixar um repositorio remoto para um repositorio local
* add : rastrear e adicionar arquivos e mudanças em relação ao que já havia resgistrado antes (stage)
* commit : salvar alterações / arquivos no repositorio local
* push : fazer upload a partir do repositorio local, enviando ao repositorio remoto
* pull : fazer download de alterações a partir do repositorio remoto até o repositorio local
* merge : mesclar codigos distintos em um só unico 
* diff : visualizar diferenças entre códigos-fonte
* log : visualizar o histórico de publicações de código-fonte 
* stash : reverte alterações referentes momentaneamente e armazenar tais alterações em memória para recuperação das alteraçõe posteriormente
