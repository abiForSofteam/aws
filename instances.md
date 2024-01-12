# Mise en place d'une instance EC2 (sur AWS)

![image](https://github.com/abiForSofteam/aws/assets/56606441/744a2fb9-5c0f-43f3-ad7d-75daffeca572)

<br />
<br />
<br />

![image](https://github.com/abiForSofteam/aws/assets/56606441/2053a582-8541-44da-9f07-3994a4ff3ad2)


<br />
<br />
<br />

![image](https://github.com/abiForSofteam/aws/assets/56606441/9d1a6728-18ae-4b4b-ae22-690996d17653)

<br />
<br />
Après avoir sélectionné notre image, nous devons renseigner les différents champs pour la mise en place de notre instance.

![image](https://github.com/abiForSofteam/aws/assets/56606441/cea22682-f84a-4947-bf19-c9776eb1f006)


<br />
<br />
Après avoir sélectionné notre VPC, 
<br />nous définissons notre sous-réseau que nous pouvons créer ou sélectionner parmi ceux proposés par AWS.
<br /> Optons pour le choix d'une attribution automatique d'une adresse ip publique.
Cette adresse ip peut nous servir entre autres, pour la connexion ssh à l'instance.
<br />La définission du groupe de sécurité pour le contrôle du trafic entrant et sortant est requise.
Sa Mise en place est développée dans la section 
[Security Group](https://github.com/abiForSofteam/aws/blob/main/security-groups.md)

<br />

![image](https://github.com/abiForSofteam/aws/assets/56606441/eaddcbc7-88d5-4e67-b77c-b2d6dc6c88ba)

<br />
<br />
Nous laissons la configuration du stockage par défaut.




