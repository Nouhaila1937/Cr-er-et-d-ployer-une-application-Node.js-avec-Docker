

# 1. Reconstruis ton image Docker :
```
docker build -t ton_nom_utilisateur/mon-app-node .

```
# 2. Lance ton conteneur à nouveau :
```
docker run -p 3000:3000 ton_nom_utilisateur/mon-app-node
```

# 3. Se connecter à Docker Hub :
```
docker login 
```
# 4.Pousser l'image sur Docker Hub :
```
docker push ton_nom_utilisateur/mon-app-node
```

![image](https://github.com/user-attachments/assets/a78512f1-fb4a-44fc-98be-464f0e88dc84)
Violà tu peux accéder à l'application sans runer l'app seulement en accédant à 
```
http://localhost:8085/
```
Résultats d'affichage 
![image](https://github.com/user-attachments/assets/c9d4cddf-a389-4f17-a129-48e5722a9da4)

# 5. Pull de l'image depuis docjer hub pour la tester directement 

```
docker pull nanga123/mon-app-node
```
