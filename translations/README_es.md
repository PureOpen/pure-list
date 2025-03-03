# PureOpen - Lista de Proyectos de Código Abierto Puro

[![English](https://img.shields.io/badge/lang-English-blue.svg)](../README.md)
[![简体中文](https://img.shields.io/badge/lang-简体中文-red.svg)](README_zh-CN.md)
[![繁體中文](https://img.shields.io/badge/lang-繁體中文-orange.svg)](README_zh-TW.md)
[![日本語](https://img.shields.io/badge/lang-日本語-green.svg)](README_ja.md)
[![한국어](https://img.shields.io/badge/lang-한국어-brightgreen.svg)](README_ko.md)
[![Español](https://img.shields.io/badge/lang-Español-yellow.svg)](README_es.md)
[![Français](https://img.shields.io/badge/lang-Français-lightblue.svg)](README_fr.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-blueviolet.svg)](README_de.md)

## Introducción al Proyecto

**PureOpen** es una organización dedicada a mantener y proteger proyectos de código abierto verdaderos. A través del proyecto **pure-list**, recopilamos y promovemos proyectos que defienden el espíritu puro del código abierto, salvaguardando los intereses de los desarrolladores y contribuyentes, y protegiendo la integridad del mundo del código abierto.

En el entorno actual de código abierto, muchos proyectos enarbolan la bandera del "código abierto" mientras en realidad están allanando el camino para la comercialización, utilizando el entusiasmo y las contribuciones de los desarrolladores como trampolín para el crecimiento corporativo. PureOpen tiene como objetivo identificar y promover proyectos que realmente siguen el espíritu del código abierto, proporcionando a los desarrolladores y usuarios una lista de referencia confiable.

## Nuestra Misión

1. **Seleccionar Proyectos de Código Abierto Puros**: Examinar y promover rigurosamente proyectos que realmente defienden el espíritu del código abierto, atrayendo a desarrolladores talentosos para participar en su mantenimiento
2. **Conectar Desarrolladores con Proyectos de Calidad**: Ayudar a desarrolladores y emprendedores a encontrar las mejores soluciones de código abierto en diversos campos
3. **Promover Contribuciones al Código Abierto**: Animar a los usuarios a contribuir a los proyectos que utilizan, formando un ecosistema de código abierto positivo
4. **Mantener los Principios del Código Abierto**: Rechazar la inclusión de proyectos "pseudo-código abierto" que planean la comercialización desde el inicio, protegiendo los derechos de los contribuyentes de código abierto
5. **Mantener Neutralidad y Objetividad**: Rechazar cualquier proyecto con inclinaciones políticas, centrándose en la transmisión de tecnología y el espíritu del código abierto

## Cómo Usar Esta Lista

Esta lista está categorizada por dominios técnicos y otras dimensiones. Puedes:
- Explorar proyectos de código abierto de alta calidad en campos específicos
- Descubrir herramientas y frameworks de código abierto emergentes y prometedores
- Encontrar proyectos que valgan la pena para contribuir y participar en la construcción de la comunidad de código abierto
- Encontrar soluciones de código abierto confiables para startups o desarrollo de proyectos

## Cómo Contribuir

Damos la bienvenida a todos para contribuir a pure-list:
1. Haz un fork de este repositorio
2. Añade proyectos de código abierto que creas que cumplen con nuestros criterios
3. Envía un Pull Request, detallando el proyecto que recomiendas y por qué cumple con nuestros criterios de inclusión
4. Nuestros mantenedores revisarán tu envío para asegurar que se alinea con la filosofía de PureOpen

## Criterios de Inclusión de Proyectos

Para que un proyecto sea incluido en pure-list, debe cumplir con las siguientes condiciones:

1. **Licencia de Código Abierto Clara**: Utiliza una licencia de código abierto reconocida (como MIT, GPL, Apache, etc.)
2. **Impulsado por la Comunidad**: Tiene contribuciones activas de la comunidad, en lugar de ser controlado por una sola empresa o individuo
3. **Intención de Código Abierto Pura**: El proyecto se estableció con el código abierto como su propósito, no como una herramienta de marketing comercial
4. **Orientado a la Tecnología**: Juzgado en base a méritos técnicos y funcionales, en lugar de política o ideología
5. **Desarrollo Sostenible**: Tiene directrices de contribución claras y planes de mantenimiento a largo plazo

## Contáctanos

Si tienes alguna sugerencia o pregunta, por favor contáctanos a través de:
- GitHub Issues: [Enviar un Issue](https://github.com/PureOpen/pure-list/issues)
- Email: [Email de Contacto]

---

# Estructura del Proyecto

## 1. Soporte Multilingüe

Para asegurar que los desarrolladores de todo el mundo puedan usar pure-list convenientemente, proporcionamos soporte multilingüe:

```
/
├── README.md (Documento principal en inglés)
├── translations/
│   ├── README_zh-CN.md (Chino simplificado)
│   ├── README_zh-TW.md (Chino tradicional)
│   ├── README_ja.md (Japonés)
│   ├── README_ko.md (Coreano)
│   ├── README_es.md (Español)
│   ├── README_fr.md (Francés)
│   ├── README_de.md (Alemán)
│   └── ... (Otros idiomas)
```

Cada versión de idioma contiene introducciones completas al proyecto, guías de uso y métodos de contribución.

## 2. Estructura de Recopilación de Proyectos

Los proyectos se categorizan por dominio y stack tecnológico, con cada archivo markdown de proyecto estructurado de la siguiente manera:

```
/
├── categories/
│   ├── backend/
│   │   ├── frameworks.md
│   │   ├── databases.md
│   │   └── ...
│   ├── frontend/
│   │   ├── frameworks.md
│   │   ├── ui-libraries.md
│   │   └── ...
│   ├── devops/
│   ├── ai-ml/
│   ├── mobile/
│   ├── desktop/
│   ├── security/
│   └── ...
└── special-collections/
    ├── newcomers.md (Proyectos adecuados para principiantes)
    ├── high-impact.md (Proyectos de alto impacto)
    ├── underrated.md (Proyectos de calidad infravalorados)
    └── needs-contributors.md (Proyectos que necesitan contribuyentes)
```

## 3. Plantilla de Entrada de Proyecto

Cada entrada de proyecto incluye la siguiente información:

```markdown
### [Nombre del Proyecto](Enlace GitHub del Proyecto)

![Stars](https://img.shields.io/github/stars/nombreusuario/proyecto?style=flat)
![Last Commit](https://img.shields.io/github/last-commit/nombreusuario/proyecto?style=flat)
![License](https://img.shields.io/github/license/nombreusuario/proyecto?style=flat)

**Introducción**: Descripción en una frase de la función principal y propósito del proyecto

**Destacados**:
- Característica 1
- Característica 2
- Característica 3

**Licencia de Código Abierto**: MIT/GPL/Apache etc.

**Actividad de la Comunidad**: Alta/Media/Baja (Basado en número de contribuyentes, tiempo de respuesta a issues, etc.)

**Adecuado para Contribuyentes**: Principiante/Intermedio/Avanzado

**Enlaces Relacionados**:
- [Documentación](Enlace a Documentación)
- [Guías de Contribución](Enlace a Guías de Contribución)
- [Comunidad/Foro](Enlace a Comunidad)

**Por Qué se Recomienda**: Breve explicación de por qué el proyecto se alinea con la filosofía de PureOpen y su valor único en el ecosistema
```

## 4. Proceso de Revisión

Para asegurar la calidad de los proyectos incluidos y su alineación con la filosofía de PureOpen, establecemos un proceso de revisión estricto:

1. **Revisión Inicial**: Comprobar si la información básica está completa y si el proyecto está activo
2. **Evaluación en Profundidad**: Evaluar la pureza del código abierto del proyecto, incluyendo historia, estructura de la comunidad, transparencia en la toma de decisiones, etc.
3. **Votación de la Comunidad**: Para proyectos controvertidos, se puede abrir una votación de la comunidad
4. **Re-revisión Regular**: Los proyectos incluidos serán re-revisados regularmente para asegurar que continúan cumpliendo con los criterios de inclusión

## 5. Construcción de la Comunidad

Para promover la filosofía del código abierto puro, haremos:

1. **Recomendaciones Regulares**: Recomendar proyectos de calidad recién incluidos mensual/trimestralmente
2. **Casos de Éxito**: Compartir historias de éxito de proyectos de calidad encontrados a través de pure-list
3. **Incentivos para Contribuyentes**: Reconocer a los desarrolladores que hacen contribuciones importantes a los proyectos incluidos
4. **Educación sobre Código Abierto**: Proporcionar recursos educativos sobre colaboración en código abierto, selección de licencias, etc.