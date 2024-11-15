

# Aplicación en ionic con autenticacion y publicacion de fotos con Firebase 📱

## Equipo de desarrollo

- [@Luis Guaygua](https://github.com/Kr-luis)
- [@Yuverly Verdezoto](https://github.com/YuverlyHidokun)

Basandonos en la [@guía](https://devdactic.com/ionic-firebase-auth-upload) realizamos la lógica y la construcción de la app

**De click [@aqui](https://github.com/Kr-luis/Repaso_firebase/blob/main/Repaso_firebase_GV.apk) para descargar la aplicación**


## Capturas de Pantalla 📸


### Enlace del funcionamiento en Youtube 

[Ver el video en YouTube](https://youtu.be/wJszaWlqqSw)

### Interfaz Principal y Auntenticacion

![login](https://github.com/Kr-luis/Repaso_firebase/blob/main/src/assets/Capturas%20de%20pantalla/login.jpeg?raw=true)

### Cloud Storage

![storage](https://github.com/Kr-luis/Repaso_firebase/blob/main/src/assets/Capturas%20de%20pantalla/storage.jpeg?raw=true)


## Pasos para configurar el Proyecto en Ionic 

1. Crear el proyecto en IONIC:
   ```bash
   ionic start nombre_aplicacion blank --type=angular
2. Entrar en el proyecto
    ```bash
    cd nombre_aplicacion
3. Dentro de de la carpeta del proyecto
   ```bash
   ionic g page login
   ionic g service services/auth
   ionic g service services/avatar
3. Instalar capacitadores 
   ```bash
   npm i @capacitor/camera
   npm i @ionic/pwa-elements
4. Añadir Firebase al proyecto 
   ```bash
   ng add @angular/fire
## Construir APK
1. Añadir capacitor de android
   ```bash
   ionic cap add android
2. Construir apk
   ```bash
   ionic build
3. Abrimos el apk en android studio
   ```bash
   ionic cap open android
