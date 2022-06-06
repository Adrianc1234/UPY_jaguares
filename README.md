# UPY PROJECT 
## Sources list


* Link para ver el tutorial completo
	- [Link del video (View)](https://www.youtube.com/playlist?list=PLP1pGkh-tN1B0fcosHdZLWZkhhnEB6xUm)


* Link para descargar el archivo web_scraping.Zip
 
	- [Web Scraping notebook (Download)](https://drive.google.com/file/d/10UHd2kdBjgw7-5Tsqqjb-FadA8Z80RBt/view)

* Link para descargar el archivo local_files.Zip 
	- [Local files for the algorithm (Download)](https://drive.google.com/file/d/1mJWbrItXURVu411AieHOUMvGitEOZZUc/view)

* Link para descargar el archivo YOLO_custom.Zip 
	- [YOLO custom files (Download)](https://drive.google.com/file/d/1gMd_JwfgOF-4kFakKjQrXiP68r2Y-0Fd/view)

* Link para descargar las imagenes ya labeleadas exp: "jaguar_0", osea se le ha ejecutado la notebook para renombrar las imagenes.
	- [Drive con imagenes (Download)](https://drive.google.com/drive/folders/1U7bozUyIZrOago1dTvKxfn30i45sTpl7?usp=sharing)
* Link para el software en dado caso que usen **linux**, los de windows en la carpeta de archivos locales anterior, ahi esta el instalador:
	- [Link de la tool para labelear (linux)](https://github.com/tzutalin/labelImg)
* Instalar el software de etiquetado de manera sencilla en linux o windows, solo ejecuten, al abrirlo se les instalara y el segundo ejecutara la ventana(`Este si trae salida para modelo YOLO`): 
```bash
$ pip3 install labelImg
$ labelImg
``` 
* Link del video principal del proceso: [Link de youtube](https://www.youtube.com/watch?v=SBNlIdAcq5k&list=PLxlDSsuQ1vid1jPLaI2Igw9gQVlG6KL6i&index=44&ab_channel=EnriqueCamacho)

**Tenemos un total de:** `1439` imagenes, las cuales dividiremos para el etiquetado con el software de arriba, una vez terminado. Practicamente ya solo nos quedara ejecutar la mitad del video. La carpeta de google drive, ya esta con la ejecucion de la primera notebook de rename, `No es necesario den rerun a la notebook`, la Segunda notebook es la del split, pero ahi se necesita tener listo todo el etiquetado.

## Fase 2 (Split samples notebook)(`Pending`)
A continuacion vamos a dividiel el labeleo de la informacion en formato para `YOLO`, como les mencione antes el software que se instala es solo corriendo ese comando y se ejecuta.

[Screenshot de donde cambiar la opcion para `YOLO`](https://snipboard.io/PLtjET.jpg)

Solo deben darles click al boton de arriba de `create reckbox` ahi al dar click cambia a `YOLO`, originalmente sale `pascalVOC`, puede que no sea en todos los casos, pero asi lo cambian.

Con el boton de `Open dir` abren la carpeta donde estan las imagenes y con el `change save dir`, es donde escogeran el lugar para guardar las imagenes, por cada imagen aprietan `w` y su mouse se pondra en forma de cruz, lo que permite marcar el area para tagear, una vez dejes de dar el click, salta un cuadro para poner tu etiqueta, en este caso la etiqueta que usaremos es: `jaguar`.

**DISTRIBUCION DEL ETIQUETADO**

- `Adrian`: `0 - 358`
- `Karla`:`359 - 718`
- `Nimbe`:`719 - 1078`
- `Pedrito`:`1079- 1439`
 