# xalapa
tutorial para la escuela de RMN de Xalapa

# instalación

Se recominda hacer la instalación en el orden mencionado!

Para comenzar es necesario instalar el [programa](https://cran.r-project.org/bin/windows/) libre de estadística R que existe para todas la plataformas, osx, linux y windows10. La última version para windows10 se encuentra [aquí](https://cran.r-project.org/bin/windows/base/R-4.0.2-win.exe).

Para simplificar el trabajo con R se recomienda utilizar un editor "especial" que ayuda a escribir los comandos y manejar los archivos. Para R ese editor se llama [Rstudio](https://rstudio.com) y también se encuentra libre para windows10 [aquí](https://download1.rstudio.org/desktop/windows/RStudio-1.3.1056.exe).

Como buena práctica para tener sus scripts al día, monitorear cambios, conservar el histórico de cambios y compartir con otros colaboradores, se recomienda usar un sistema que maneja las versiones, uno de esos sistemas es "Git", que igualmente es libre y existe para todas la plataformas. [Aquí](https://gitforwindows.org/) para windows10.

Finalmente, para simplificar el trabajo con Git se puede utilizar un software adicional como [tortoiseGit](https://tortoisegit.org/) que permite usar Git desde el explorador de archivos, sin tener que aprender los comandos de Git.

Una vez instalado estos software o por lo menos los 2 primeros, R y Rstudio, se puede iniciar este último y copiar los comandos siguientes en la consola. Deberá seleccionar un servider de donde conectar para instalar los paquetes adicionales.

```r
install.packages(c("rmarkdown", "plotly", "websocket", "rstudioapi", "Numero", "car", "git2r", "xml2"))
```

```r
install.packages(c("BiocManager"))
BiocManager::install(c('pcaMethods', 'impute', 'MassSpecWavelet'))
```

```r
install.packages(c("devtools"))
devtools::install_github('kimsche/MetaboMate')
devtools::install_github('jwist/hastaLaVista')
```

Puede tardar varios minutos para instalar todas esta bibiotecas adicionales.