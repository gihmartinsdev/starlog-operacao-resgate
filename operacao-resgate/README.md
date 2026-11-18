# Operação Resgate • StarLog-Zero

Motor de dados da estação de cargas (model, exception, main), sem JDBC.

## Compilar e executar (terminal, na raiz do projeto)
```
javac -encoding UTF-8 src/br/com/starlog/model/*.java src/br/com/starlog/exception/*.java src/br/com/starlog/main/*.java
java -cp src br.com.starlog.main.MainResgate
```
Resultado esperado: os 4 ataques do Chaos Monkey com ✅ SUCESSO.
