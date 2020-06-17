## Definindo roteamento estático

### Pré requisitos

Primeiro precisa entrar no modo de configuração do terminal

```
enable

conf t
```

Você pode configurar tanto pelo gateway quanto pela porta destino.

### Definindo pelo gateway

```
ip route <REDE DESTINO> <MÁSCARA DE SUB-REDE> <GATEWAY>
```

### Definindo pela endereço de próximo salto

```
ip route <REDE DESTINO> <MÁSCARA DE SUB-REDE> <ENDEREÇO DE PRÓXIMO SALTO>
```