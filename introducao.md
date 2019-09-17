# Node.js

Como um ambiente de execução Javascript assíncrono orientado a eventos, o Node.js é projetado para desenvolvimento de aplicações escaláveis de rede.

Node.js é semelhante no projeto, e influenciado por sistemas como Event Machine do Ruby ou Twisted do Python. Porém, leva o modelo de eventos um pouco mais além. No Node.js o event loop é exposto como uma parte do ambiente de execução ao invés de uma biblioteca. Em outros sistemas há sempre uma chamada bloqueante para iniciar o event-loop. Tipicamente o comportamento esperado é definido através de callbacks no início do script, e no final um servidor é iniciado por uma chamada bloqueante.

Em Node.js, HTTP é um cidadão de primeira classe, projetado para que tenha um alta taxa de fluxo e baixa latência. Isso torna o Node.js uma ótima escolha para servir como base para uma biblioteca web ou para um framework.

- [História] (/wiki/nodejs/historia)
