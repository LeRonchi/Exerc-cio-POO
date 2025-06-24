
# 💻 Exercicio4POO - Classe Invoice em Java

Este projeto foi desenvolvido como parte dos estudos de Programação Orientada a Objetos (POO) na linguagem Java. O objetivo principal é representar uma fatura (`Invoice`) com atributos e métodos que seguem boas práticas de encapsulamento e validação.

## 🧠 Conceitos aplicados

- Criação de classes com atributos privados
- Encapsulamento com métodos `get` e `set`
- Validação de valores (quantidade e preço unitário não podem ser negativos)
- Método personalizado `getInvoiceAmount()` para calcular o valor total da fatura

## 🧾 Estrutura da Classe

```java
public class Invoice {
    private int codigoItem;
    private String descricao;
    private int quantidade;
    private float precoUnitario;

    // Construtor, getters, setters e método getInvoiceAmount()
}
```

## 📁 Organização

```
Exercicio4POO/
├── src/
│   └── Invoice.java
└── README.md
```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone git@github.com:LeRonchi/Exerc-cio-POO.git
   ```

2. Importe o projeto no NetBeans ou qualquer IDE Java.

3. Compile e execute um programa de teste que instancie a classe `Invoice`.

## 🛡️ Validações

- Quantidade menor que 0 → assume 0
- Preço unitário menor que 0 → assume 0

## 📚 Autor

**Leandro Ronchi**  
Estudante de Análise e Desenvolvimento de Sistemas  
👨‍💻 Interesse em infraestrutura, suporte e desenvolvimento em Java
