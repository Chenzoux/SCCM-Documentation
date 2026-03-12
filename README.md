# SCCM-Documentation
CMtrace
Cuando no esta instalado CMtrace se localiza en \SMSSETUP\TOOLS

Dato en la instalacion, a la hora de instalar para evitar el error durante la instalacion del MECM, existe un fallo inicial que impide instalar el msoledbsql requiere la instalacion del Visual C++ 2022 redistributable para continuar. Otro punto es que no instala por un bug con el ODBC driver, la versio actual tiene un bug que impide continuar la instalacion la version especifica debe estar por debajo de la 18.5 en este enlace: https://www.fileeagle.com/software/download/19860/200532 se encuentra una descarga fiable y funcional.
