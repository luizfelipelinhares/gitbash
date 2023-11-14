# gitbash
Instruções GitBash

[Clonar Repositório](#clonar-repositorio)  
[Criar Branch](#criar-nova-branch)  
[Mudar de Branch](#mudar-de-branch)  
[Deletar Branch](#deletar-branch)  
[Commits](#commits)  
[Verificar arquivos modificados](#verificar-arquivos-modificados)  
[Adicionar arquivos para commit](#adicionar-arquivos-para-commit)  
[Commit](#commit)  
[Upload para o github](#upload-para-o-github)  
[Merge](#merge)  
[Renomear um arquivo](#renomear-um-arquivo)

Para concluir as modificações, precisa dar commit e push.  
Ordem das coisas: 
1. git add \<Nome do arquivo modificado\>
2. git commit -m "seu commit aqui"
3. git push

<hr>

### **Clonar repositório**
-git clone \<link do repositório\>

## Branches

### Ver todas as branches
-git branch

### Criar nova branch

-git branch \<nome da branch\>  
-git push origin \<nome da branch\>


### Mudar de branch

-git checkout \<nome da branch\>


### Deletar branch

Deletar a banch no servidor do github  
-git push -d origin \<nome da branch\>

## Commits

### Verificar arquivos modificados

-git status  

### Adicionar arquivos para commit

-git add \<arquivo\>  

-git add --all

### Commit

-git commit -m \<Descrição do commit\>

## Upload para o GitHub

-git push

## Merge

-git merge \<branch de origem\>

## Renomear um arquivo

-git mv \<nome_Antigo\> \<nome_novo\>

## Git fetch

Baixar todos os arquivos do repositório sem atrapalhar os já modificados no pc  
-git fetch --ALL

## Apagar pastas

-git rm -r \<Nome da pasta\>

## Apagar Arquivos

-git rm \<Nome da pasta\>
