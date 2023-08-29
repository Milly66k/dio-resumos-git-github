
# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre o Git e GitHub
do curso Versionamento de Código com Git e GitHub

[Digital innovation DIO](https://web.dio.me/)

## 📚 Documentação
- [Documentação Git](https://git-scm.com/docs/git/pt_BR)
- [Documentação GitHub](https://docs.github.com/pt)

## 💻Resmos das Aulas

|Aulas | Resumos |
|------|---------|
|Caderno de estudos | [Resumo](https://www.notion.so/Cardeno-de-Estudos-ad2b4880c1a54ff797f007a7919dea26)
|Portifolio| [Link](https://milly66k.github.io/Portifoli-Milly-Souza/)

```
git init
git add .
git commit -m 'nome do seu commit'
gith push 
```

## 🔍 Referências 
- [Cubos Academy](https://aulas.cubos.academy/turma/b820e8f4-402e-4a7e-bd3f-a2b4d2d1b029)
- [Dio](https://web.dio.me/home)

```
Dicas:
cls - ctrl + l - clear - São formas de limpar o terminal

git init - inicializa um repositorio git
git clone - clona um repositório
git add . - adiciona os arquivos na area de preparação
git commit -m 'nome do commiit' - faz um commit e salva tudo que ta na area de preparação
git push - empura os commit para o repositorio remmoto
git pull - puxa do remoto para o local

git config - configuraçoes do git, pode se global, sistema ou local
git config --global user.name 'Milly' - salva o seu nome
git config --global user.email 'lauraa9lemos@gmail.com' - salva o meu email
git config user.name - ver o nome que ta salvo
git config user.email - ver o email que ta salvo
git config init.defaultbranch - ele retorna o nome da nossa branch padrao
git config --global init.defaultbranch main - muda para main a nossa branch padrao
git config --global  --list - lista todas alteraçoes feitas
git config --global credential.helper store - salva o tokem 
git config --global --show -origin credential.helper - mostra aonde fica

cat git confing - mostra aonde fica
cat git -credetials - onde esta o tokem
ls -a ~/ .ssh - ver se tem uma chave ssh
$ - indica o inicio de um novo comando
ssh-keygen - ele que gera a nossa chave shh
-t ed25519 - o tipo do algoritimo
-c - vai ser um comentario que indica o propietario
'seu email' - propietario

mkdir - cria uma pasta
cd ou cd.. - entra e sai de uma pasta
git remote -v - ele te mostra qual repositorio esta ligado
git remote add origin 'ponhe a Url' - conecta o local com o remoto
git clone URL --branch 'master' --singl-branch - clona uma branch especifica
git status - mostra o estado dos seu arquivos
touch README.md - cria um arquivo reademe vazio
git add README.md - aiciona um arquivo especifico
git log - mostras os commits feitos
echo resumos/ > .gitignore - cria o git ignore e ponhe a pasta resumos dentro dele
echo > .gitignore - deixa o gitignore vazio
touch aulas/ .gitkeep - ponhe o gitkeep dentro do arquivo aulas para não deixa a pasta vazia

rm -rf .git - remove um arquivo a força nesse caso o .git
git restore - retorna para a ultima modificação
git commit --amend -m 'nome do novo commit' - troca o nomde o ultimo commit feito
git reset --soft 'ponhe o head do commit que vc quer alterar' - apaga o ultimo commit e ponhe ele na area de preparação
git reset --mixed 'ponhe o head aqui' - apaga o ultimo commit mas não ponhe ele na area de preparação, se quiser por de volta tem que dar um git add .
git reset --hard 'ponhe o head aqui' - ele apaga definitivamente todos os arquivos e o commit
git reflog - ele mostra os commits de forma mais detalhada
git restore --staged 'o nome do arquivo' - tambem deleta o arquivo defitivamente mas é mais complicado
git reset 'e o nome do arquivo' - deleta o arquivo especifico

git remote add origin URL - concta do local para o remoto
git branch -M main - muda a branch para main
git push -u origin main - da um git push e ja conect com o repositorio remoto

```



