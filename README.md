# Text Mining
Author Profiling

Este trabajo ha sido realizado por:
- Jose Eduardo Reinoso Andrade
- Carlos Peiro Gonzalez
- Eusebio Soriano Benegas
- Sergio Roca

Para ejecutar el codigo implementado pan-ap17.r:
- Abrir R studio
- Ejecutar todo el código
- Si se quieren modificar parámetros, solo se modificarán en la sección (parámetros) marcada dentro del código.

En este repositorio se incluyen los siguientes archivos.
- Codigo implementado: pan-ap17.r
- Papper generado: Papper.pdf
- Presentación hecha en clase: TextMinig.pptx
- Archivo de instrucciones: intrucciones de ejecucion.txt


  
Los parametros que se pueden modificar son:

```{r}
# **************************************************************************
# ***********************   PARAMETROS     *********************************
# **************************************************************************
# Preparacion de parametros, estaticos
lang <- "es"
path_training <- "C:/Users/ASUS/Documents/Master Big Data/Text Mining en Social Media/pan-ap17-bigdata/training"
path_test <- "C:/Users/ASUS/Documents/Master Big Data/Text Mining en Social Media/pan-ap17-bigdata/test"
param.eliminarAcentos <- FALSE
param.lowcase <- FALSE
param.punctuations <- TRUE
param.numbers <- TRUE
param.whitespaces <- TRUE
param.swlang <- "es"
param.swlist <- c("si","q","d","via")
param.verbose <- FALSE
param.genero <- ""
```
