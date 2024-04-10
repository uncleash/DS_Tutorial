---
title: "Content"
chapter: true
weight: 80
---

### Demo Script files structure

```
genesys-demo-script
├───content
│   ├───en-US
│   │   ├───010-Introduction
│   │   ├───020-Getting-Started
│   │   └───090-Conclusion
│   └───es-ES
│       ├───010-Introduction
│       ├───020-Getting-Started
│       └───090-Conclusion
└───static
    ├───css
    └───images

```
  
### Images

You should work with "Content" folder seen in the repository structure above. 

The demo script images should be added to the "Images" subfolder under the "Static" folder. Once the images are uploaded to this folder, you can begin referencing them using markdown language.

Add images to the demoscript files in markdown format pointing to 'images' folder:

```
![Images](/images/some-image.png)
```

Here is an example of linking image:

```
[![Logo](/images/genesys-logo.png)](http://genesys.com)
```

You can think of the folders within "Content" as modules. For example, if you wanted to add a module about "Setting Up", you would add a folder to the "Content folder" and title it "030-Setting Up". You would then add your information to that module. The number before the title signifies the order of that module. So "030-Setting Up" would come after "020-Getting Started" and before "090-Conclusion".

You can then organize your content within that folder by adding [markdown](https://www.markdownguide.org/basic-syntax) files. 

> **_NOTE:_** You can add HTML tags to the markdown document when you need an additional formatting

To add a markdown file, right click the folder you want this file to appear in and select "New File". Give the submodule a title that reflects its numerical order followed by ".md". For example, if you wanted the module "020-Getting Started" to have 2 "submodules", you would title the first one  "10_first.md" and the second one "20_second.md". (Note: files have to end in ".md" for the system to recognize it as a markdown file).

![Submodules](/images/structure.png)

To add information to your module's landing page, you can edit the "index.md" file. For example, if I wanted my "030-Setting Up" landing page to have an objective, welcome, etc, I would add that to the "index.md" file.

![Index](/images/intro.png)

### Brunch Titles

"Title" in an md file header will be shown as a name of the branch in the Demo Script navigation tree.

```
--- _index.md ----
title: "Introduction"
chapter: true
weight: 10
...
------------------
```