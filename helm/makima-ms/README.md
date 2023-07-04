## Help commands 

# Criando pacote:

1. ```cd helm```
1. ```helm package makima/ms```
1. Mova a versão criada para o repositório makima-ms
1. No repositório makima-ms:
    - ```helm repo index makima-ms/ --url https://denjidev.github.io/makima-ms/```
    - Faça o commit da alteração e espera as actions rodarem. 
    - Happy helming :D
