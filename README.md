# RGB-LED
RGB LED 

## Cómo funcionan los LEDs RGB y cómo controlar el color.
### ¿Qué es un LED RGB y cómo funciona?
Un LED RGB es básicamente un paquete de LED que puede producir casi cualquier color. Puede ser utilizado en diferentes aplicaciones como la iluminación de decoración al aire libre, diseños de iluminación de escenarios, iluminación de decoración del hogar, pantalla de matriz LED, y más.

Los LEDs RGB tienen tres LEDs internos (Rojo, Verde y Azul) que pueden ser combinados para producir casi cualquier salida de color. Con el fin de producir diferentes tipos de colores, tenemos que ajustar la intensidad de cada LED interno y combinar las tres salidas de color. En este tutorial, vamos a utilizar PWM para ajustar la intensidad de los LEDs rojo, verde y azul individualmente y el truco aquí es que nuestros ojos verán la combinación de los colores, en lugar de los colores individuales porque los LEDs están muy cerca uno del otro en el interior.

### Tipos y estructura de los LEDs RGB
Como se mencionó anteriormente, los LEDs RGB tienen tres LEDs en su interior y, por lo general, estos tres LEDs internos comparten un ánodo común o un cátodo común, especialmente en un paquete de agujeros pasantes. Así que, básicamente, podemos clasificar los LEDs RGB como de tipo ánodo común o cátodo común al igual que en las pantallas de siete segmentos.
[![RGB-LEDs-Pinout.png](https://i.postimg.cc/7h2YLqh7/RGB-LEDs-Pinout.png)](https://postimg.cc/xN9SxDKT)

LED RGB de ánodo común
En un LED RGB de ánodo común, los ánodos de los LEDs internos están todos conectados al cable de ánodo externo. Para controlar cada color, es necesario aplicar una señal BAJA o tierra a los cables rojo, verde y azul y conectar el cable del ánodo al terminal positivo de la fuente de alimentación.

LED RGB de cátodo común
En un LED RGB de cátodo común, los cátodos de los LEDs internos están todos conectados al cable de cátodo externo. Para controlar cada color, es necesario aplicar una señal HIGH o VCC a los cables rojo, verde y azul y conectar el cable del ánodo al terminal negativo de la fuente de alimentación.

Traducción realizada con la versión gratuita del traductor www.DeepL.com/Translator


Referencias:
https://www.circuitbread.com/tutorials/how-rgb-leds-work-and-how-to-control-color 
