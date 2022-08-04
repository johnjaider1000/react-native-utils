# Instalaciones recomendadas - React Native

## Instalaciones Necesarias

* [Visual Studio Code](https://code.visualstudio.com/)

* [Insomnia](https://insomnia.rest/download)

* [Mongo Compass](https://www.mongodb.com/try/download/compass)

* [Brew - Solo para Mac/IOS](https://brew.sh/index_es)

* [Git](https://git-scm.com/)
```
git config --global user.name "Tu nombre"
git config --global user.email "Tu correo"
```

* [Node](https://nodejs.org/es/)

* [Android Studio](https://developer.android.com/studio)

* [XCode - SOLO en MAC OSX](https://apps.apple.com/ca/app/xcode/id497799835)


## Extensiones de VSCode
[Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)

### Configuración del Bracket Pair Colorizer 2

[Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
```
"bracket-pair-colorizer-2.colors": [
    "#fafafa",
    "#9F51B6",
    "#F7C244",
    "#F07850",
    "#9CDD29",
    "#C497D4"
],
```
### Tema que estoy usando en VSCode:

* [Monokai Night](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-monokai-night)

* [Iconos](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

### Instalaciones recomendadas sobre React y React Native

* [ES7 React/Redux](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)

* [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [TypeScript importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)


#
#
#

# Librerías probadas 2022 que vas a necesitar para el desarrollo:

* [React-Native-Bootsplash](https://github.com/zoontek/react-native-bootsplash): Nos permitirá poner un splash a nuestra aplicación, si requiere ayuda con la integración ver este [vídeo](https://www.youtube.com/watch?v=PlubOKfi46o). Recordar que para IOS hay que usar el archivo `BootSplash.storyboard` y agregarlo con xcode a la lista de recursos de la aplicación, en el vídeo se explica esto de una manera clara.

* Otra herramienta que puedes usar para un Splash mas avanzado se explica en este [articulo](https://blog.logrocket.com/building-a-splash-screen-in-react-native/#:~:text=tutorials%20on%20GitHub.-,How%20to%20build%20a%20splash%20screen%20in%20React%20Native,depending%20on%20your%20internet%20speed.)


# Solucionar problemas de integración:

* Algunas veces te encontrarás con problemas de AndroidStudio, generalmente suelo utilizar la herramienta para perfilar mi aplicación, firmala y demás, Me he encontrado con algunos problemas dónde puedes obtener mensajes como:
 `React Native on Android: Cannot run program "node": error=2, No such file or directory`. Esto generalmente lo he solucionado facilmente abriendo android con el siguiente comando, aquí básicamente le damos permiso a Android Studio de acceder con un poco más de permisos y de esta manera se soluciona el problema sin liarse con más cosas:

```bash
$ open -a /Applications/Android\ Studio.app
```

* Adicionalmente a veces veremos el mensaje: ```This version of the Android Support plugin for IntelliJ IDEA (or Android Studio) cannot open this project, please retry with version 2021.1.1 or newer.```, este mismo lo he solucionado dirigiendome a la pestaña File/Project Structure de Android Studio y actualizando la versión de Android Gradle Plugin Version a la 7.0.3, esto ha funcionado para mí.
