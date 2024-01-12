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

### Après avoir sélectionné notre image, nous devons renseigner les différents champs pour la mise en place de notre instance.

![image](https://github.com/abiForSofteam/aws/assets/56606441/cea22682-f84a-4947-bf19-c9776eb1f006)


<br />
<br />
Après avoir sélectionné notre VPC (celui par défaut, ou celui éventuellement mis en place par nos soins), 
<br /> - nous définissons notre sous-réseau que nous pouvons créer ou sélectionner parmi ceux proposés par AWS.
<br />  - Optons pour le choix d'une attribution automatique d'une adresse ip publique.
Cette adresse ip peut nous servir entre autres, pour la connexion ssh à l'instance.
<br /> - La définission du groupe de sécurité pour le contrôle du trafic entrant et sortant est requise.
Sa Mise en place est développée dans la section 

[Security Group](https://github.com/abiForSofteam/aws/blob/main/security-groups.md)

<br /><br />

![image](https://github.com/abiForSofteam/aws/assets/56606441/eaddcbc7-88d5-4e67-b77c-b2d6dc6c88ba)

<br />
<br />
Pour l'exemple, nous laisserons par défaut les paramètres qui suivent, notamment ceux relatifs à la configuration du stockage.
<br />Ensuite nous validons pour la création de l'instance EC2.

<br />
<br />

### Instance en cours de création

![image](https://github.com/abiForSofteam/aws/assets/56606441/fdb76df6-df21-41ab-a736-eb866947dafa)


<br />
<br />

### Instance en cours d'exécution

![image](https://github.com/abiForSofteam/aws/assets/56606441/9b221786-1f46-43ae-a794-53d15b60576c)





