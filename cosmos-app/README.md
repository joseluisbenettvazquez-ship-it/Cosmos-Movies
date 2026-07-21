# Cosmos — cómo generar el .exe, el .dmg y el .apk

No necesitas escribir ni una línea de código. Vas a subir estos archivos a GitHub
(gratis) y un robot los va a compilar por ti. Tarda unos 10-15 minutos.

## Paso 1: crear una cuenta en GitHub
Entra a https://github.com y crea una cuenta gratis (si ya tienes una, sáltate este paso).

## Paso 2: crear un repositorio nuevo
1. Dale clic al botón verde "New" (o entra a https://github.com/new).
2. Ponle de nombre, por ejemplo, `cosmos-app`.
3. Puede ser público o privado, cualquiera funciona.
4. Dale a "Create repository". No marques ninguna otra opción.

## Paso 3: subir los archivos
1. En la página del repositorio recién creado, busca el enlace que dice
   "uploading an existing file" (o ve a "Add file" → "Upload files").
2. Arrastra **toda la carpeta `cosmos-app`** que te di (con todo lo de adentro:
   `desktop`, `mobile`, `.github`, este mismo README) directo a esa página.
   Es importante que se mantenga la misma estructura de carpetas.
3. Abajo, dale a "Commit changes" (puedes dejar todo como está, solo confirma).

## Paso 4: esperar a que compile solo
1. Ve a la pestaña "Actions" arriba en el repositorio.
2. Vas a ver que ya empezó a correr un proceso llamado "Build Cosmos". Dale clic.
3. Espera a que los tres trabajos (Windows, macOS, Android) terminen con un ✔️ verde.
   Puede tardar entre 10 y 15 minutos.

## Paso 5: descargar tus instaladores
1. Dentro de esa misma pantalla del proceso terminado, baja hasta la sección
   "Artifacts" (al final de la página).
2. Vas a ver tres archivos para descargar: `Cosmos-Windows`, `Cosmos-macOS` y
   `Cosmos-Android`. Descárgalos — cada uno es un .zip que trae adentro el
   .exe, el .dmg o el .apk.

## Notas importantes

- **Windows**: al abrir el .exe por primera vez, es probable que aparezca un
  aviso de "Windows protegió tu PC" (porque no está firmado con un certificado
  pagado). Dale a "Más información" → "Ejecutar de todas formas". Es normal
  para apps personales sin firmar, no significa que tenga virus.
- **macOS**: al abrir el .dmg e instalar la app, es probable que macOS diga
  que no puede verificar al desarrollador. Haz clic derecho sobre la app →
  "Abrir" → confirmar. Solo hay que hacerlo la primera vez.
- **Android**: el .apk no viene de la Play Store, así que Android va a pedir
  que actives "Instalar apps de fuentes desconocidas" la primera vez. Es
  normal para apps instaladas por fuera de la tienda.
- Si en el paso de Android la cámara o el micrófono no funcionan al primer
  intento, dímelo — es la parte más delicada de todo el proceso y puede
  necesitar un ajuste fino.
