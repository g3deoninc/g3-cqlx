# Paquete Común de CQL de G3deon Inc

![Banner del repositorio](/assets/g3-cqlx-banner.png)

## Traducciones

Puedes ver la documentación en tu idioma preferido:

- Español. (Traducción actual)
- Inglés. [Ver en Inglés](/README.md).
- Portugués (Brasil). [Ver en Portugués](/README-BR.md).

## Preguntas Frecuentes (FAQs)

### ¿Por qué g3-cqlx?

En [G3deon Inc](https://g3deon.com) tenemos una arquitectura distribuida, específicamente de micro servicios. Al no trabajar con un monorepo, nos hemos dado cuenta de que en muchos de nuestros micro-servicios hemos repetido mucho código. En vista de este escenario, para mejorar la mantenibilidad y la escalabilidad de nuestro servicio, hemos separado este código repetido en bibliotecas. De aquí surge **g3-cqlx**, una biblioteca para la integración de cqlx con los estándares que seguimos en [G3deon Inc](https://g3deon.com).

### ¿Por qué no usar gocqlx directamente?

Con **g3-cqlx**, nuestro objetivo es tener las funciones más repetidas, pero eso no impide que se pueda utilizar [gocqlx](https://github.com/scylladb/gocqlx) directamente. Puedes hacerlo, pero también puedes utilizar las funciones de g3-cqlx si vas a realizar acciones básicas y repetitivas.

## Licencia

Este proyecto está bajo la *Licencia MIT*.

```md
Licencia MIT

Copyright (c) 2024 G3deon, Icon.

Se concede permiso, de forma gratuita, a cualquier persona que obtenga una copia
de este software y los archivos de documentación asociados (el "Software"), para tratar
el Software sin restricciones, incluyendo, sin limitación, los derechos
para usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar y/o vender
copias del Software, y para permitir a las personas a las que se les proporcione el Software
para hacerlo, sujeto a las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso se incluirán en todos
copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA,
INCLUYENDO PERO NO LIMITADO A LAS GARANTÍAS DE COMERCIABILIDAD,
APTITUD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO EL
LOS AUTORES O TITULARES DE DERECHOS DE AUTOR SERÁN RESPONSABLES DE CUALQUIER RECLAMO, DAÑO U OTRO
RESPONSABILIDAD, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE OTRO MODO, DERIVADA DE,
FUERA DE O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTROS NEGOCIOS EN EL
EL SOFTWARE.

```

