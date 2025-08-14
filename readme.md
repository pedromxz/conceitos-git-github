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

Verificar a situação do repositório (pasta) usamos o status a qualquer momento.
```bash
git status
```

Adiciona arquivos ao versionamento.
```bash
git add .
```

Salva as alterações de arquivos.
```bash
git commit -m "Criação do Arquivo"
```