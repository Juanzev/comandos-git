# comandos-git 

1. **Iniciar Git**:
   - `git init` - Inicia um novo repositório Git no diretório atual.

2. **Clonar um repositório**:
   - `git clone [URL]` - Clona um repositório Git existente para o diretório local.

3. **Adicionar alterações**:
   - `git add [arquivo]` - Adiciona alterações ao índice (staging area) para prepará-las para o commit.

4. **Realizar commit**:
   - `git commit -m "mensagem"` - Realiza um commit com as alterações adicionadas, incluindo uma mensagem que descreve as alterações feitas.

5. **Verificar o status**:
   - `git status` - Exibe o estado atual do repositório, mostrando quais arquivos foram modificados, adicionados ou removidos.

6. **Histórico de commits**:
   - `git log` - Mostra o histórico de commits do repositório.

7. **Listar branches**:
   - `git branch` - Lista todas as branches locais e destaca a branch atual.

8. **Criar uma nova branch**:
   - `git branch [nome-da-branch]` - Cria uma nova branch.

9. **Alterar de branch**:
   - `git checkout [nome-da-branch]` - Altera para uma branch específica.

10. **Mesclar branches**:
   - `git merge [branch]` - Combina as alterações de uma branch para a branch atual.

11. **Atualizar repositório local**:
   - `git pull` - Atualiza o repositório local com as alterações do repositório remoto.

12. **Enviar alterações para o repositório remoto**:
   - `git push [remote] [branch]` - Envia os commits locais para o repositório remoto.

13. **Verificar repositórios remotos**:
   - `git remote -v` - Lista os repositórios remotos configurados.

14. **Recuperar alterações do repositório remoto**:
   - `git fetch` - Recupera as últimas alterações do repositório remoto, mas não faz a mesclagem automaticamente.

15. **Desfazer alterações no arquivo**:
   - `git reset [arquivo]` - Desfaz as alterações no arquivo especificado, removendo-o do índice.

16. **Remover arquivo**:
   - `git rm [arquivo]` - Remove um arquivo do repositório e inclui no próximo commit.

17. **Comparar alterações**:
   - `git diff` - Mostra as diferenças entre as alterações que ainda não foram adicionadas ao índice.

18. **Adicionar repositório remoto**:
   - `git remote add [nome-remoto] [URL]` - Adiciona um repositório remoto com um nome específico.

19. **Push para o repositório remoto**:
   - `git push origin main` - Envia as alterações locais para o repositório remoto.
