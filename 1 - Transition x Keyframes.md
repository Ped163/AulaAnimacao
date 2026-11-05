### **1 - Transition x Keyframes**





###### **Trasition**(animação por estado):



A transição acontece quando algo munda de um estado para outro.





**exemplo:**

.botao{

&#x09;background-color: blue;

&#x09;transition: background-color 0.5s ease;

}



.botão:hover{

&#x09;background-color: red;

}

\------------------------------------

###### **Keyframes** (animação autônoma):



A animação acontece sozinha.





**exemplo:**



@keyframes piscar {

&#x09;from{

&#x09;opacity:1

&#x09;}



&#x09;to {

&#x09;opacity:0;

&#x09;}

}



###### **2. A regra transition completa** 





Transition: Propriedade; duração; curva.







O "curva" contém: 

**ease**: Começa devagar, acelera e termina devagar;

**linear**: Velocidade constante; 

**ease-in:** começa lento;

**ease**-**out**:Termina lento ;

**ease-in-out**:Começa e termina lento;













