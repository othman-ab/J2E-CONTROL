Bienvenue dans notre application de commerce électronique basée sur des microservices, utilisant des technologies telles que Consul Discovery, Spring Cloud Config, Spring Cloud Gateway, Angular et d'autres services spécifiques.

Archithecture:

![td4](https://github.com/othman-ab/J2E-CONTROL/assets/68157094/b6538941-7a04-45b1-8cf7-eb008520630c)

Commandes pour démmarrer consul :

>consul.exe agent -dev


Commandes pour vault :

>cd C:\Program Files\vault_1.15.2_windows_386<br>
>vault server -dev
>set VAULT_ADDR=http://127.0.0.1:8200
>vault kv get secret/billing-service

