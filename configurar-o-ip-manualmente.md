## Comandos para poder configurar as redes

```
enable

configure terminal 
```

## Selecionando a interface

Qual interface está conectada a máquina que você quer atribuir o ip?

Caso não saiba como ver, olhe nas observações.

Exemplo com a interface f0/0:

```
interface f0/0
```

## Adicionando ip e mascara

Você precisa descobrir respectivamente o primeiro ip da rede e máscara da máquina que você está tentando conectar.

Exemplo com o ip 172.20.0.1 e máscara 255.255.255.128:

```
ip add 172.20.0.1 255.255.255.128
```

## Caso queira adicionar uma descrição

```
description <SUA DESCRIÇÃO AQUI>
```

## "Salvando" as configurações

```
no shut
```

Após "salvar" você pode configurar multiplas outras máquinas antes de sair do módo de configuração do terminal.

## Fechando configurações

```
exit
```