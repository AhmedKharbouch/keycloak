# keycloak configuration


## Start Keycloak
> kc.bat start-dev
>![keycloak start](https://user-images.githubusercontent.com/102327247/211333695-01f4df38-83bb-4276-886d-8046fd6deebd.PNG)
## Creation du Realm
> Realm : my-ecom-realm
>![realm](https://user-images.githubusercontent.com/102327247/207452154-c9168eb7-459e-41ba-8265-e0e0e00338d1.PNG)
## Creation des clients
>![client](https://user-images.githubusercontent.com/102327247/207452312-271ea201-af77-4b62-a360-6c0ac177863e.PNG)
## Creation des Users
>![users](https://user-images.githubusercontent.com/102327247/207452393-76e25b03-5c82-489c-a085-fdc374b6bb9d.PNG)
## Creation des Roles
>![roles](https://user-images.githubusercontent.com/102327247/207452434-495b47f1-449c-411b-92fb-65e7f9e58000.PNG)
## Affectation des Roles
>affectation du role USER au user1

> 1/2

>![user1](https://user-images.githubusercontent.com/102327247/207452519-4156a125-dbb1-46bf-94fa-9006ba0f91b9.PNG)
>affectation du role ADMIN et MANAGER et USER au user3

> 2/2

>![user2](https://user-images.githubusercontent.com/102327247/207452659-f24f9b2a-9a6e-4423-a6c5-b0b2c34ac77f.PNG)

## Authentification to Keycloak
>authentification with ARK plugin same as Postman
>>send Post request to keycloak

>>1/2

>>![auth1](https://user-images.githubusercontent.com/102327247/211334110-8913d610-8e4c-4229-b5f1-01575ef3b733.PNG)

>>2/2

>>Acces Token Received
>>![auth2](https://user-images.githubusercontent.com/102327247/211334384-5c4ed066-7933-4523-9b01-a86eae03bc93.PNG)

## Show what inside the access Token with JWT.io

>>1/2

>>![jwt1](https://user-images.githubusercontent.com/102327247/211334792-232ca571-9187-4420-a02c-39f4734bdb5e.PNG)

>>2/2

>>![jwt2](https://user-images.githubusercontent.com/102327247/211334830-5c3b328f-276a-437f-8ec8-93c10c0804c5.PNG)




