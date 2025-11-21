# Desafio-War-Estruturado-c
Cada fase introduz novos conceitos de programação, evoluindo de estruturas básicas até um sistema completo com gerenciamento dinâmico de memória e lógica complexa de jogo.
# 🎲 War Estruturado - Sistema de Estratégia Militar

## 📋 Visão Geral
Projeto acadêmico desenvolvido em linguagem C que implementa um sistema completo baseado no jogo War, evoluindo através de três fases com complexidade crescente. Cada etapa introduziu novos conceitos de programação estruturada, gerenciamento de memória e design de sistemas.

---

## 🏗️ **FASE 1: Fundamentos e Estruturas Básicas**

### **Objetivos Principais**
- Introdução ao conceito de structs em C
- Manipulação de arrays estáticos
- Implementação de cadastro e exibição de dados

### **Funcionalidades Implementadas**
- ✅ Struct `Territorio` com nome, cor e tropas
- ✅ Cadastro de 5 territórios via input do usuário
- ✅ Exibição formatada dos dados cadastrados
- ✅ Validações básicas de entrada

### **Conceitos Aplicados**
```c
// Estrutura fundamental
struct Territorio {
    char nome[30];
    char cor[10];
    int tropas;
};
