# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de Git e Github.

## Configuração Inicial
Rode os comandos abaixo no terminal(cmd) do seu computador.
```bash
git config --global user.name "Pedro Mussio De Freitas"

git config --global user.email pedromfreitas200@gmail.com
```


## Comando do Git
Iniciar o GIT em uma pasta do computador utilizamos o init.
**IMPORTANTE**: Só é executado 1 vez.
```bash
git init 
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no GitHub e seguir a segunda opção da lista de comandos que aparece no site.
**IMPORTANTE:** Depois do remote deve ser executados os outros 2 comandos da página
```bash
git remote add origin < url_repositorio_github >
```


Verificar a situação do repositório (pasta) usamos o status a qualquer momento.
```bash
git status
```

Quando o status mostrar arquivos em vermelho é necessário rodar o **add** para adicionar os arquivos a serem salvos. **.** adiciona todos os arquivos da pasta. **add .**
```bash
git add .
```

Salvar uma versão dos arquivos na situação atual usamos o commit o -m adiciona uma mensagem do porque estes arquivos estão sendo salvos.
```bash
git commit -m "Criação do Arquivo"
```

Baixar as alterações que estão apenas no Github utilizamos o pull. <br>
**IMPORTANTE:** Sempre deve baixar a ultima versão da nuvem antes de enviar a atual do computador.
```bash
git pull
```

Enviar os commits do pc para o GitHub utilizamos o push.
```bash
git push
```


