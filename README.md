# manual
Documentación viva de nuestra metodología de trabajo.

Este es un documento vivo que describe workflows, herramientas y otras yerbas en torno a nuestra forma de trabajar desde el desarrollo hasta la implementación continua.

La idea es documentar el estado y evolución de nuestra metodología como referencia interna del equipo y al mismo tiempo compartir nuestras estrategias con todo aquel que quiera aprovecharlas, discutirlas, etc.

Elijo este formato en lugar de utilizar un wiki por dos motivos:
+ Permite apreciar la evolución histórica del documento.
+ Resulta conveniente y oportuno para ejercitar nuestro workflow basado en github.

## Objetivo

Nos proponemos adoptar mejores prácticas, procesos, cultura y metodología tomados del movimiento open source para aplicarlos al desarrollo de software en el sector público.

De manera similar a como el movimiento [inner source](http://paypal.github.io/InnerSourceCommons/index.html) refresca las prácticas en las empresas privadas en pos aumentar su eficiencia y calidad, nos valemos de estos recursos para ganar en economía, agilidad y calidad en el estado.

## Filosofía

## Entrega contínua

## Chat Ops

## Arquitectura

## Dependencias

## Guías de estilo

## Documentación

## Tests

## Control de calidad

## Workflow

1º- Le pedimos a Juanito que nos prepare un pipeline de entrega contínua para alguno de los siguientes tipos de proyectos:
    + Módulo javascript.
    + Aplicación javascript.
    + Módulo php.
    + Aplicación php.
    + Módulo hubot.

2º- Unos segundos después, Juanito nos provee la url del nuevo repositorio junto con instrucciones para empezar a trabajar.

3º- Clonamos el repositorio.

4º- Instalamos dependencias.

5º- Creamos un branch de nombre descriptivo.

6º- Codeamos actualizando tests y documentación para reflejar los cambios.

7º- Ejecutamos git push origin <nombredelbranch>.

8º- Se ejecutan una serie de validaciones automáticas.

9º- Se crea pull request.

10º- Se valida el código en el servidor de integración (travis.ci).

11º- Si todo anduvo bién, Juanito avisa a los responsables de realizar la revisión de pares.

12º- Una vez aprobada la pull request se publica una nueva versión, respetando versionado semántico, que se pone en producción automáticamente.

13º- Juanito avisa que se ha publicado una nueva versión y felicita al autor.

## Diseño / Experiencia de usuario

## Código de conducta
