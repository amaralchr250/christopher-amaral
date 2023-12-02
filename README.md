# Prezados, segue a documentação e arquitetura resumida do desafio:

Foi subido a instância no lightsail e feito até o passo 5 da documentação:

https://lightsail.aws.amazon.com/ls/docs/pt_br/articles/amazon-lightsail-tutorial-launching-and-configuring-wordpress

![image](https://github.com/amaralchr250/christopher-amaral/assets/42553791/b6619a55-3537-4900-b60e-36e030e25d50)

Acesso a instância como também a chave SSH adicionado dentro da branch.

Segue o comando para realizar dentro da pasta na qual vai ter o arquivo com extensão ".pem"

````
ssh -i LightsailDefaultKey-us-east-1.pem bitnami@52.4.84.5
````

User:devopsjr or user
Password:Fic8Af2ltpdu48adlN1Roeb5 / aI.lhVjiH!r8

Segue o Print da tela como também a url:

http://52.4.84.5/wp-login.php

![image](https://github.com/amaralchr250/christopher-amaral/assets/42553791/eb7516af-4891-4c03-b9aa-041c1327233c)

![image](https://github.com/amaralchr250/christopher-amaral/assets/42553791/d14024c9-ef09-428e-85b9-a8e78b9fedcd)

# Como extra vou deixar Docker-Compose se caso subir um EC2 já irá ter para executar dentro e um shell script para rodar também.

![image](https://github.com/amaralchr250/christopher-amaral/assets/42553791/19d1338c-ea65-47e4-8510-93d7c07b000c)

Já está dentro da instância para validar os dois arquivos.

````
sh wordpress.sh
````

### Entrega
1. Efetue o fork deste repositório e crie um branch com o seu nome e sobrenome. (exemplo: fulano-dasilva)
2. Após finalizar o desafio, crie um Pull Request.
3. Aguarde algum contribuidor realizar o review.
4. Dados de acesso do WordPress e Lightsail com tudo configurado e funcionando
5. Prints e url "http://PublicIpAddress/wp-login.php"
6. Documentação (Opcional)
7. Arquitetura (Opcional)
8. Plugin informado arrumado e versionado
9. Suba o plugin para a sua instalação WordPress Lightsail e ative o mesmo.
