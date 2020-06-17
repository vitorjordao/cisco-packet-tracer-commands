É necessário fazer a configuração dos ips previamente

## Adicionando na tabela de roteamento

```
router rip

version 2
```

## Adicionando a rede:

```
network <IP DA REDE>
```

Você pode adicionar várias redes antes de fechar a trabela de roteamento.

## Fechando a tabela de roteamento

```
exit
```

## Adicionando o eigrp

```
router eigrp 1
```

## adicionando as redes

```
network <IP DA REDE>
```

Você pode adiocionar várias redes antes de finalizar as configurações.

## Fechando a tabela do eigrp

```
exit
```