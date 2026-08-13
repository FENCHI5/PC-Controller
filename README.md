# PC-Controller

Controlá el mouse y teclado de tu PC desde el celular por WiFi. Pensado para saltar intros/recaps de Netflix y otras plataformas.

## Descargar

Los dos van en la sección [Releases](https://github.com/FENCHI5/PC-Controller/releases/latest), bajate el que corresponda:

- **`PC-Controller-Setup.exe`** → instalás esto en tu PC (Windows).
- **`PC-Controller-Android.apk`** → instalás esto en tu celular (Android). No está en Play Store, así que Android te va a avisar "desarrollador desconocido" al instalarlo — es esperable, tocá igual "Instalar".

## Cómo funciona
- Instalás `PC-Controller-Setup.exe` en tu PC.
- El programa corre en la bandeja del sistema y te muestra una ventana con la **IP** y el **PIN** de tu PC.
- En el celular, abrís la app (o el navegador, si no instalaste el APK, entrando a `http://<esa-IP>:8765`), ingresás la IP y el PIN, y ya podés controlar la PC.

> La PC y el celular deben estar en la misma red WiFi.
> El PIN evita que otro dispositivo de la red controle tu PC sin que lo autorices — se genera solo la primera vez y queda fijo.
