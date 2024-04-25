

atalho para log personalizado 
''' git config --global alias.hist 'log --pretty=format:"%h %ad | %s%d [%an]" --graph --date=short' '''



# Nota: configuração para push de commits e tags simultaneamente

Para adicionar a configuração a um repositório local específico, acesse o repositório e execute:

git config --local push.followTags true

Para adicionar a configuração a todos os repositórios do seu usuário corrente do sistema operacional execute:

git config --global push.followTags true

Para adicionar a configuração a todos os repositórios de todos os usuários do sistema operacional execute:

git config --system push.followTags true 

# Mudar para commit 

git switch "commit que eu desejo" -- detach   