# Desplegando aplicaciones con Open Application Model

El API de Kubernetes provee de multitud de entidades que nos permiten definir cómo queremos desplegar los servicios de una aplicación. Sin embargo, el API standard no provee de una abstracción a nivel de aplicación completa. Esto dificulta la gestión de las aplicaciones desplegadas en un cluster, y preguntas como "¿esta mi aplicación funcionando?" se traducen en la necesidad de identificar y monitorizar entidades de bajo nivel para obtener una visión global. Además, algunas de las entidades más utilizadas requieren anotaciones específicas dependendiendo del proveedor utilizado. Open Application Model aborda estos problemas introduciendo abstraciones a nivel aplicación, así como extensiones a nivel de componente agnósticas del proveedor. Esto reduce la curva de aprendizaje de Kubernetes para nuevos usuarios y flexibiliza el despliegue en distintos proveedores.

# Cómo lanzar los ejemplos

Con la cuenta gratuita del NAPPTIVE Playground se obtiene un cluster Kubernetes que dispone de soporte incorporado para OAM. El [getting started](https://docs.napptive.com/Getting_started.html) oficial contiene los pasos detallados para acceder al playground, instalar el CLI y poder lanzar los ejemplos.

1. Signup con GitHub para obtener una cuenta gratuita en [https://playground.napptive.dev/](https://playground.napptive.dev/).
2. Instalación del CLI

```
$ curl -O https://storage.googleapis.com/artifacts.playground.napptive.dev/installer.sh && bash installer.sh
```

3. Login desde el CLI

```
$ playground login
```

4. Lanzar el ejemplo

```
$ playground catalog deploy napptive/wordpress-mysql:5.7.0
```

Para acceder utilizando `kubectl` el comando `playground get-kubeconfig` permite recuperarlo.


# Sobre el evento

* [Kubernetes Community Days Spain - KCD](https://kcdspain.com/)
* [CNCF Community Group](https://community.cncf.io/events/details/cncf-kcd-spain-presents-kubernetes-community-days-spain)


