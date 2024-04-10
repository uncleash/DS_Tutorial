---
title: "Localization"
chapter: true
weight: 80
---

## Languages  

Each language content should be placed under a special folder under 'content' directory. The folder have must be be same as language code, like 'en-US' or 'pr-PR'. The structure of language folders is simalar, the only difference is translated md files. 

Images for different languages can be the same or different. In the second case they should be placed to static/images folder with new names, like '*popup.png*' and '*es-popup.png*'.

### Adding new language

To add a new language:

- if you don't have an access to GTS git repository, download the demo script spurce using Download button on a demo script tile (click on demo title to expand the tile before that).

![Download](/images/download.png)

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

Send updated demo script to [GDemo team](mailto://tm@genesys.com)
