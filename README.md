# codigo-seg-line-arduino

## Codigo Exemplo (template)

```ino

void setup()
{
  /*A função setup() é chamada quando um sketch inicia. 
  Use-a para inicializar variáveis, configurar o modo 
  dos pinos(INPUT ou OUTPUT), inicializar bibliotecas,
  etc. A função setup() será executada apenas uma vez, 
  apoós a placa ser alimentada ou acontecer um reset.*/
  
  pinMode(2, OUTPUT);
}


void loop()
{
  
  	/*Depois de criar uma função setup(), a qual 
    inicializa e atribui os valores iniciais, a 
    função loop() faz precisamente o que o seu 
    nome sugere, e repete-se consecutivamente 
    enquanto a placa estiver ligada, permitindo 
    o seu programa mudar e responder a essas mudanças. 
    Use-a para controlar ativamente uma placa Arduino.*/
  
    digitalWrite(2, HIGH);
    delay(1000);

    digitalWrite(2, LOW);
    delay(1000);               
}
```

## Circuito
![image](https://github.com/Fabio-jr-SM/codigo-seg-line-arduino/assets/91484736/181f2c20-aa56-4246-98b5-a74f7633d95d)
