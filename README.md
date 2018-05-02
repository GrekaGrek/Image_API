# Image_API

Tech Rerequirements:

- Spring boot
- Spring data
- H2 DB
- React, Redux


Bussiness requirements:

UI
- See list of images with preview (Preview depending on image size)
- Upload images with name and tag(can be empty)
- Search engine - prefix/tags 


Other requirments:
- use git
- jQuerry not allowed
- Format ALL code (Java, HTML, Js , etc.)
- use GULP or Webback, BOWER, NPM
- all HTML logic must be writen on React
- Files in frontend should be loaded in this sequence: html, css, js
- All Java clases must be placed in specific packages
- Use Jersey (NOT SPRING MVC)
- Wild card import NOT allowed
- Special file system for images -> upload image, get link

REST end points:
GET /images/ (all image metedata)
GET /image/$id/ (returns image metadata)
GET /image/$id/png (returns actual image)
PUT /image/$id/  (returns image metadata)
POST /image (returns image metadata)


1) Separate
    - FE service (return static files)
    - BE service (parse REST requests return JSON)
2) Add Logging
3) Optimize imports (remove all unused imports)
4) Custom exception mappers in Jersey
5) All build files in separate directories
6) Java conventions for components (Correct class names)
