
# Sobre o Git

Git é uma ferramenta de versionamento que visa facilitar o desenvolvimento de projetos. O Git permite que você crie várias linhas do tempo para seu projeto, sendo possível retroceder nelas a qualquer momento. Isso não só pode deixar seu ambiente de desenvolvimento mais seguro, como também facilita a colaboração nos projetos, já que o trabalho de cada um pode ser dividido em várias linhas do tempo.

# Sobre o GitHub

O GitHub é uma plataforma em nuvem e gratuita que permite hospedar seus repositórios Git. Sem plataformas assim, não seria possível, por exemplo, que várias pessoas de lugares diferentes do mundo trabalhassem em um mesmo projeto como o Linux. Caso não existissem, cada projeto teria que investir em seu próprio servidor Git para manter seus dados e possibilitar a colaboração à distância.

## Como começar um projeto no GitHub

Primeiro, crie um repositório (assim são chamados os locais onde ficam armazenados os arquivos do seu projeto) no GitHub, depois crie um repositório local no seu computador com o Git. Agora, basta conectar ambos com o link do repositório do GitHub.

Por exemplo:

```sh
# Inicia o repositório Git
git init
# Conecta o repositório local com o GitHub
git remote add origin https://github.com/username/repository.git
# Adiciona arquivos ao repositório e aplica as mudanças
git add .
git commit -m "Primeiro projeto com Git"
# Manda as mudanças para a nuvem
git push -u origin master
```
