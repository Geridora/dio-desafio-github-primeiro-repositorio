# Anotações do sobre Git/GitHub
[Link para download do Git](https://git-scm.com/downloads)
### Git Bash é um terminal extendido para otimizar o uso do Git.

## Alguns comandos básicos do terminal

- **git init** - cria uma pasta oculta .git e inicia um repositório local;
- **git add** - adiciona um arquivo para o estado de espera (para que seja guardado como o mais recente) ao git que o mesmo não possuía conhecimento prévio ou que sofreu alguma modificação ao estado anterior determinado;
- **git status** - mostra o monitoramento/status dos arquivos contidos naquele diretório;
- **mkdir** - cria uma nova pasta naquele diretório;
- **mv nomeDoArquivo ./nomeDaPasta/** - move o arquivo indicado para a pasta indicada através do comando;
- **ls** - lista os itens contidos no diretório atual (pastas e arquivos);
- **ls -a** - lista as pastas ocultas do diretório atual;
- **cd nomeDaPasta** - entra no diretório indicado;
- **cd ..** - volta ao diretório anterior;
- **git rm nomeDoArquivo** - remove um arquivo do repositório;
- **echo > nomeDoArquivo.tipoDoArquivo** - cria um arquivo no diretório atual;
- **git add * / git add .** - adiciona todos os arquivos que sofreram alterações dentro do repositório para o estado de espera para que seja guardado/atualizado;
- **git commit -m "mensagem"** - "commita" o repositório, tornando-o a versão mais recente e atualizada do mesmo;
- **git config --list** - lista as configurações atuais do Git;
- **git config --global --user.email seuEmail@email** - guarda um email como o autor do repositório e dos arquivos daquele local;
- **git config --global --user.name seuNome** - guarda um nome para o autor das modificações realizadas no repositório;
- **git config --global --unset user.email** - apaga o email indicado anteriormente;
- **git config --global --unset user.name** - apaga o nome de usuário indicado anteriormente;
- **git remote add origin linkDoGitHub** - indica para onde os arquivos do repositório local serão enviados para o repositório remoto;
- **git push origin master** - envia os arquivos da "branch" atual (master) que foram modificados e que estão "commitados" para o repositório remoto;
- **git pull origin master** - pega o arquivo do repositório remoto e o transfere para o seu repositório local;
- **git remote -v** - mostra para onde os repositório estão apontando remotamente.