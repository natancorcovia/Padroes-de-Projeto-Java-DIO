# Projeto Singleton em Java

Este projeto contém três implementações do padrão Singleton em Java, com o objetivo de demonstrar suas diferenças em termos de inicialização, thread-safety e eficiência.

## Implementações

### 1. Singleton Eager
- Instância criada no carregamento da classe.
- Thread-safe.
- Instância criada mesmo que não seja usada.

### 2. Singleton Lazy
- Instância criada somente quando necessária (lazy initialization).
- Não thread-safe.
- Pode causar problemas em ambientes multithread.

### 3. Singleton Lazy Holder
- Utiliza uma classe interna estática para criação lazy e thread-safe.
- Não requer sincronização explícita.
- Abordagem eficiente e recomendada para uso em multithread.

## Uso

Basta chamar o método estático `getInstancia()` da classe desejada para obter a instância singleton.

## Objetivo

Comparar diferentes formas de implementar Singleton, entendendo vantagens, desvantagens e aplicações.

---
