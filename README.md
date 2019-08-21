# Como funciona o led RGB?

Na aula de hoje, vocês vão aprender a utilizar o Led RGB!​​

Aprenda como utilizar o LED RGB integrado a uma placa Arduino Uno, utilizando as saídas PWM para demonstrar as cores emitidas do componente. Por meio do monitor serial, o Arduino lerá o nome da cor escrita pelo usuário e, por meio do LED RGB, a cor digitada será reproduzida.​

# O que é um LED? O que significa o termo “LED”?

LED é uma sigla para Light Emitting Diode que em português significa Diodo Emissor de Luz. O LED é um componente eletrônico que, quando ocorre passagem de corrente elétrica, emite luz. Possui dois terminais, chamados de anodo (positivo) e catodo (negativo).

LED é uma sigla para Light Emitting Diode que em português significa Diodo Emissor de Luz. O LED é um componente eletrônico que, quando ocorre passagem de corrente elétrica, emite luz. Possui dois terminais, chamados de anodo (positivo) e catodo (negativo).

![LED 1](https://i1.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2017/10/of_Led.svg.png?resize=158%2C356&ssl=1)

# O que é um LED RGB?

Assim como os LEDs tradicionais, o LED RGB emite luz por meio da passagem de corrente elétrica, mas ele apresenta a peculiaridade de ser composto por três LEDs de cores diferentes, sendo elas: vermelho (Red), verde (Green) e azul (Blue), surgindo daí o nome “RGB”.

![LED 2](https://i1.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2018/02/2da19fe0a2.jpg?resize=284%2C284&ssl=1)

# LED RGB

Cada LED pode ser controlado de maneira individual, conectando apenas os seus terminais em alguma fonte de energia, deixando os outros desconectados, mas o seu grande diferencial está em justamente utilizar os três ao mesmo tempo, no qual utilizando pulsos PWM (recomendamos que veja o tutorial Arduino – Grandezas digitais, analógicas e PWM) para realizar o controle de intensidade de cada cor individualmente, de modo que, a cor resultante será a mistura das cores emitidas por cada LED.

![LED 3](https://i1.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2018/02/RGB_LED_anim.gif?resize=527%2C200&ssl=1)

Demonstração do resultado da mistura de intensidades diferentes das cores: vermelho, verde e azul

# Tipos de LED RGB

Por se tratar da associação de três LEDs distintos em um único LED, eles podem ser denominados de: catodo comum ou anodo comum, sendo o catodo comum o mais utilizado.

![LED 4](https://i1.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2018/02/rgb.jpg?resize=300%2C177&ssl=1)

# Descrição dos pinos

O tipo catodo comum possui uma interligação entre os catodos dos três LEDs, fazendo com que se torne apenas um. Já o tipo anodo comum apresenta uma interligação entre os anodos dos três LEDs, tornando-o apenas um, como é possível visualizar na figura abaixo.

![LED 5](https://i0.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2018/02/LED-RGB-tipos.png?resize=300%2C191&ssl=1)

# Tipos de LED RGB

Para identificar o terminal que equivale ao comum, basta ver qual terminal é o maior, ou ver qual está conectado a maior “placa” presente no interior do LED, como é possível ver na ilustração abaixo.

![LED 5](https://i1.wp.com/portal.vidadesilicio.com.br/wp-content/uploads/2018/02/img01_arduino_utilizando_led_rgb_catodo_anodo_comum.png?resize=390%2C301&ssl=1)

Identificação de cada pino​