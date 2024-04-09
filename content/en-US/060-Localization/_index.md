---
title: "Localization"
chapter: true
weight: 80
---

## Languages  

Each language content should be placed under a special folder under 'content' directory. The folder have must be be same as language code, like 'en-US' or 'pr-PR'. The structure of language folders is simalar, the only difference is translated md files. 

Images for different languages can be the same or different. In the second case they should be placed to static/images folder with new names, like '*popup.png*' and '*es-popup.png*'.

### Adding a new language

To add a new language:

- copy content of 'content/en-US' folder
- translate md files in the copy
- put translated files under 'content/[localization code]' folder
- update config.toml file with new language section, like for 'es-ES':

```
[Languages.es]
contentDir = 'content/es-ES'
title = "Serie de talleres Genesys"
description = "En este taller, aprenderá cómo crear un taller desde cero usando Github y algunas otras herramientas"
weight = 2
languageName = "Español"
languageCode = "es-ES"
```

Send updated files to tm@genesys.com
