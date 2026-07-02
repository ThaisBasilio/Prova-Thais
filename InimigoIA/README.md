1- Para mudar a branch para uma nova chamada feature-ia-inimigo precisamos utilizar o comando git checkout -b feature-ia-inimigo
Depois para criar o arquivo InimigoIA.cs no terminal utilizamos o comando dotnet new console -n InimigoIA. Para verificar se está na branch corret você utiliza o comando git branch

2- Primeiro você utiliza o comando git status para verificar o status atual do repositório. Para adicionar apenas a parte referente ao codigo do InimigoIA utilizamos o comando git add InimigoIA.cs e para confirmar a alteração você utiliza o comando git commit -m "Adicionando o codigo do InimigoIA"

3- Para isto nós utilizamos o comando git log

4- Para voltar a branch main utilizamos o comando git checkout main e realizar o merge utilizamos o git merge. Utilizamos o git status para verificar se há algum arquivo conflitante, e depois de corrigir caso tenha algum utilizamos o git add [nome do arquivo] e depois git commit

5- Para adicionar o comando ao stage utilizamos o comando git add InimigoIA.cs, depois utilizamos git comit -m "Refatoração: Adicionado método de verificação de saúde".

6- Letra B, git restore InimigoIA.cs

7- Para criar uma tag leve (lightweight) utilizamos o comando git tag  v1.0 e para criar uma tag anotada utilizamos git tag -a v1.0 -m "Lançamento da versão 1.0"

8- Utilizamos o comando git remote add origin [URL do repositorio]

9- Utilizamos o comando git push -u origin feature-ia-inimigo 
