## Comandos do git


#### iniciar o git na aplicação
```bash
git init
```

### verificar o que foi alterado
```bash
git status
```

### adicionar alteraçoes na staging area
```bash
# "." podendo ser tbm o nome do arquivo
git add . 
```

### salvar alterações
```bash
## MSG sendo sua mensagem
git commit -m "MSG"
```

### listar branches
```bash
git branch
```

### criar uma branch
```bash
# sendo NAME o que nome que quero para minha branch
git checkout -b NAME
```

### navegar para um branch branches
```bash
# sendo NAME o nome da sua branch
git checkout NAME
```

### merjar branch
```bash
# sendo NAME o nome da branch que vc quer merjar
git merge NAME
```