# Aula Git 

![](/gif/git.png)

## Comandos git:

- **Git init**: Inicia o projeto git.

- **Git status**: Nos mostra o status desse repositório.
    * A nossa Branch;
    * Mudanças para serem adicionadas.

    ![](/gif/2.PNG)

    * Mudanças já adicionadas.

    ![](/gif/4.PNG)
    

- **Git log**: Nos mostra a linha de tempo de commit.

    ![](/gif/1.PNG)

- **Git log --oneline**: Mostra a linha do tempo reduzida.

    ![](/gif/5.PNG)

- **Git add**: Adiciona os arquivos no modo storage (staging).
    * git add < file>;
    * git add . (tudo).

- **Git rm --cached < file>**: Remove o arquivo que adicionamos.

- **Git diff**: Mostra as diferenças que teve no work para o commit.

    ![](/gif/3.PNG)

- **Git Config**: Para configurar.
    * git config user.name "JeanCigoli";
    * git config user.email "jeancigoli30@gmail.com".

- **Git commit -m "Mensagem"**: Para fazer o commit.

- **Git checkout < identificação do commit >**: Muda para onde o Head vai apontar, podendo voltar a versão anterior.

- **Git checkout < branch>**: Para mudar de branch.

- **Arquivo .gitignore**: Para colocar os arquivos que serão ignorados.

- **Git Branch < name>**: Para criar uma nova branch passando o name sem espaço. 

- **Git merge < branch>**: Para subir as novas atualizações de um branch para a que você deseja.

- **Git branch -D < branch>**: Para deletar uma branch que não está mais em uso

- **Git remote add origin < link>**: Para adicionar um link remote ao seu reporitório.

- **Git remote -v**: Para mostrar os link remotos.

- **Git push origin master**: Para subir seu arquivo para o repositório.

- **Git fetch**: Baixa as atualizações feitas em outro lugar e deixa em standby.

- **Git diff origin/< branch>**: Mostra as diferenças entre as duas branch, serve antes de dar o pull.

    ![](/gif/6.PNG)

- **Git pull origin master**: Pegar os dados novos da branch e fazer o merge com o seu.