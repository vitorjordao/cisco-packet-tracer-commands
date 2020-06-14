## Mudando a senha e o secret

### Pré requisitos

Primeiro precisa entrar no modo de configuração do terminal

```
enable

conf t
```

### Mudando a senha

```
enable password <SUA SENHA AQUI>

login
```

### Mudando o secret

```
enable secret <SEU SECRET AQUI>
```

### Removendo a senha

```
no enable password
```

### Removendo o secret

```
no enable secret
```

## Configurando senha do terminal

### Pré requisitos

Primeiro precisa entrar no modo de configuração do terminal e na linha 0

```
enable

conf t

line console 0
```

### Configurando a senha propriamente dita

```
password <SUA SENHA AQUI>

login

end
```
