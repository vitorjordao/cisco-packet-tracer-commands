É necessário fazer a configuração dos ips previamente

## Adicionando na tabela de roteamento

```
router rip

version 2
```

## Adicionando a rede:

```
network 172.20.0.0
```

Você pode adicionar várias redes antes de fechar a trabela de roteamento.

## Fechando a tabela de roteamento

```
exit
```

## Adicionando o ospf

```
router ospf 1
```

## adicionando as redes

Obs. A máscara é inverssa ex.

Cálculo:
```
255.255.255.255
-
255.255.255.128
_______________
0.0.0.127
```

O comando fica assim:

```
network 172.20.0.0 0.0.0.127 area 0
```

Você pode adiocionar várias redes antes de finalizar as configurações.

## Fechando a tabela do ospf

```
exit
```