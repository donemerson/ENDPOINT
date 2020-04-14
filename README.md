# Sorteio Deboni

## Endpoints

> Todas as chamadas para API precisam começar com a URL base: 
>
|     Nome      |                  URL                   |
| :-----------: | :------------------------------------: |
| Play Serviços | https://teste.playservicos.com.br:3001 |


> Resumo de nossos end points
> 
|      NOME       | METHOD |                URL                |       BODY        |      HEADER       |     RESPONSE      |
| :-------------: | :----: | :-------------------------------: | :---------------: | :---------------: | :---------------: |
|      LOGIN      |  POST  |      ``{{URL}}/sessions?=``       | [EXEMPLO](#login) | [EXEMPLO](#login) | [EXEMPLO](#login) |
|  LIGAR SORTEIO  |  GET   |  ``{{URL}}/sorteio/DEMO/ligar``   |    [EXEMPLO]()    |    [EXEMPLO]()    |    [EXEMPLO]()    |
|  MARCAR NUMERO  |  POST  |  ``{{URL}}/sorteio/DEMO/marcar``  |    [EXEMPLO]()    |    [EXEMPLO]()    |    [EXEMPLO]()    |
| ENCERRAR PRÊMIO |  GET   | ``{{URL}}/sorteio/DEMO/encerrar`` |    [EXEMPLO]()    |    [EXEMPLO]()    |    [EXEMPLO]()    |

## Documentação

#### LOGIN
>   
>  
> ## Body
> ~~~javascript
> {
>	"email": "example@domain.com",
>	"password": "YOUR_SECRET_PASSWORD"
>}
> ~~~
> ## Header
> 
> |KEY|VALUE|
>| :---:|:--:|
>|Content-Type|application/json|
> 
> ## Response successful
> ~~~javascript
>{
>    "token": {
>        "type": "bearer",
>        "token": "YOUR_GENERATE_TOKEN",
>        "refreshToken": null
>  },
>   "user": {
>       "username": "YOUR_USERNAME",
>       "email": "example@domain.com",
>       "praca_id": null,
>       "profile_id": YOUR_PROFILE_ID,
>       "id": YOUR_ID,
>       "praca": null
>    }
>}
>~~~
>## 
> ## 

## Postman
> Caso você utilize postman, veja como importar nossa collection
1. Baixe o Postman nesse [link](https://www.postman.com/downloads/)
2. Importando collection
   1. Copie o texto raw desse [link](https://www.getpostman.com/collections/a0879b2bcece01bcbb22) e cole no campo abaixo 
   2. ![Foto](https://raw.githubusercontent.com/donemerson/assets/master/play_servicos/tempsnip.png)


  
