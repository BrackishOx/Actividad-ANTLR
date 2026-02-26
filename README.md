# Calculadora ANTLR e

Implementación de la calculadora del Capítulo 4 usando ANTLR 4.13.2 con Java.

## Generar parser
antlr4 -visitor Calc.g4

## Compilar
javac -cp ".:/usr/local/lib/antlr-4.13.2-complete.jar" *.java

## Ejecutar
java -cp ".:/usr/local/lib/antlr-4.13.2-complete.jar" Main
