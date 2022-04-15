# Notas interessantes em relação ao Git/GitHub (Versão Windows 11)

### - Adicionar o Git Bash ao novo terminal do Windows 11: <https://www.timschaeps.be/post/adding-git-bash-to-windows-terminal/> (tutorial em inglês).

<br> 

### - Durante as aulas introdutórias o professor comparou alguns comandos básicos entre o Windows e o Linux, como:
`dir` x `ls`

`del` x `rm`
### Porém com o novo terminal do Windows podemos usar (através do PowerShell) alguns comandos que não são permitidos no cmd (como o próprio ls).
### Inclusive podemos usar todos os comandos do bash através do WSL (Windows Subsystem for Linux): <https://docs.microsoft.com/en-us/windows/wsl/install>

<br>

### Sobre um erro encontrado durante um git clone no meu repositório através do link Https: corrido ao atualizar o origin através do comando `git remote set-url origin seu-link-do-repositorio-versao-ssh-aqui.git`