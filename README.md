# FaceRecognition
CV2 Face Recognition

Pasos:

1. Clonar repositorio

```
git clone https://github.com/AlexanderPrincipe/FaceRecognition.git
```

2. Ir a la ruta del programa

```
cd FaceRecognition/
```

3. Crear una carpeta llamada 'att_faces', dentro de esta crear la carpeta llamada 'orl_faces', luego dentro de esta crear otra carpeta con su nombre. Por ejemplo, la carpeta 'AlexanderPrincipe'. El orden de las carpetas debe quedar como en la siguiente imagen.

```
- mkdir att_faces

- cd att_faces

- mkdir orl_faces

- cd orl_faces

- mkdir AlexanderPrincipe
```

![Captura de pantalla de 2020-03-28 23-12-09](https://user-images.githubusercontent.com/31213239/77840170-d2b74980-7149-11ea-807d-e5c614808656.png)

2. Luego, el programa tomara 100 fotos con el siguiente comando, estas 100 fotos le servira como input para poder reconocer rostros.
```
python capture.py AlexanderPrincipe
```

2. El software de reconocimiento ya tendrá como input las 100 fotos tomadas, ahora toca correr el siguiente comando para reconocer rostros.

```
python reconocimiento.py
```
