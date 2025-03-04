# CPions_Shinylive  
The app can be opened here: https://wbs-tw.github.io/CPions_Shinylive/  
You can then run the app locally in your computer without installing it on RStudio.  

  
Some tutorial for deploying shinylive in github:  
https://hbctraining.github.io/Training-modules/RShiny/lessons/shinylive.html  
https://github.com/RamiKrispin/shinylive-r  
  
  
  
Creation of this serverless github pages was made using the following steps from the above tutorials:  
  
`library(shinylive)`  
`library(httpuv)`  
`shinylive::export(appdir = "..FULLPATH/CPions_Shinylive/", destdir = "docs")`  
where ..FULLPATH is the path in the local computer  

`httpuv::runStaticServer("docs/", port = 8008)`

