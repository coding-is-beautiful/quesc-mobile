## Inicializando a máquina do vagrant

``` bash
# Acessar a pasta vagrant.
cd vagrant

# Rodar o comando abaixo para subir a máquina.
vagrant up
```

Aguarde o setup da maquina, pode demorar bastante dependendo da velocidade da internet.

## Acessando a máquina

``` bash
# Rodar o seguinte comando depois do 'vagrant up' concluído. 
vagrant ssh
```

## Rodando o projeto
``` bash
# Dentro da máquina, acessar a pasta project
cd /project
# Rodando o comando do ionic
ionic serve
```
