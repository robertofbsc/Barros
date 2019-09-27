# Barros
Testando
void setup() 
{
    
    pinMode(LED, OUTPUT); //Instrução para colocar o gpio que iremos utilizar como saída, ou seja, podermos alterar seu valor
    //livremente para HIGH ou LOW conforme desejarmos
}
//Função que é executada continuamente, começando da primeira instrução em sequência até a última. 
//Quando a última instrução é executada a primeira instrução é executada novamente
//e assim por diante enquanto o programa estiver rodadando
void loop() 
{
   
    digitalWrite(LED, HIGH);  //Faz com que o sinal do gpio escolhido seja alto, fazendo com que o led acenda
    delay(1000);              //Espera 1000 milésimos de segundo, ou seja 1 segundo, para executar o próximo comando
    digitalWrite(LED, LOW);   //Faz com que o sinal do gpio escolhido seja baixo, fazendo com que o led apague.
    delay(1000);              //Espera 1000 milésimos de segundo, ou seja 1 segundo, para executar o próximo comando.
                             //Depois de executada a última instrução do loop o programa irá retornar para a primeira instrução
}
     
