# Principais Comandos para Git e GitHub

## Comandos Básicos do Git

 teste para alteração

1. **Configuração Inicial**
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@example.com"

2. **Inicializar um Repositório**
   ```bash
   git init

3. **Clonar um Repositório**
   ```bash
   git clone https://github.com/usuario/repo.git  

4. **Verificar o Status do Repositório**
   ```bash
   git status

5. **Adicionar Arquivos ao Índice (Stage)** 
    ```bash
    git add nome_do_arquivo
    git add .  

6. **Fazer um Commit**    
    ```bash
    git commit -m "Mensagem do commit"

7.  **Verificar o Histórico de Commits** 
     ```bash
     git log

8.   **Criar uma Nova Branch**   
     ```bash
     git branch nome_da_branch

9.    **Mudar para uma Branch**   
       ```bash
      git checkout nome_da_branch

10.   **Criar e Mudar para uma Nova Branch**
      ```bash
      git checkout -b nome_da_branch

11. **Mesclar uma Branch**
      ```bash
      git merge nome_da_branch

12. **Excluir uma Branch**
     ```bash
     git branch -d nome_da_branch

13. **Adicionar um Repositório Remoto**   
     ```bash
     git remote add origin https://github.com/usuario/repo.git

14. **Verificar Repositórios Remotos**
     ```bash
     git remote -v

15. **Enviar Commits para o Repositório Remoto**
    ```bash
    git push origin nome_da_branch

16. **Atualizar o Repositório Local com Alterações do Remoto** 
     ```bash
     git pull origin nome_da_branch

17. **Reverter um Commit** 
     ```bash 
      git revert hash_do_commit

18. **Resetar para um Commit Específico**
     ```bash
     git reset --hard hash_do_commit
     git reset -- soft hash_do_commit
     git reset -- mixed hash_do_commit

 19. **Verificar Diferenças Entre Commits ou Branches**    
      ```bash
      git diff

 20. **Stash: Salvar Alterações Temporariamente**
     ```bash
     git stash
     git stash pop