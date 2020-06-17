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

## Criptografar a senha caso necessário

```
service password-encryption
```

## Configurar uma senha para as conexões VTY (terminal virtual ou telnet)

### Pré requisitos

Primeiro precisa entrar no modo de configuração do terminal

```
enable

conf t
```

### Para configurar nos roteadores

```
line vty 0 4

password <SUA SENHA AQUI>

login
```

### Para configurar nos switches

```
line vty 0 15

password <SUA SENHA AQUI>

login
```

## Salvando as configurações

```
copy running-config startup-config
```