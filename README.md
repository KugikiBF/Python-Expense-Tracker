# Projeto: Gerenciador de Despesas (CLI) em Python

Este projeto é um "Expense Tracker" (Gerenciador de Despesas) completo, desenvolvido em Python e executado inteiramente via linha de comando (CLI).

O objetivo é demonstrar o uso de estruturas de dados fundamentais (listas e dicionários) e conceitos de programação funcional (`map`, `filter`, `lambda`) para criar uma aplicação interativa e modular.

---

## 📖 Sobre o Projeto

O script simula um sistema onde o usuário pode gerenciar suas despesas financeiras. O estado da aplicação (as despesas) é mantido em memória (em uma lista de dicionários) enquanto o programa está em execução.

O código é dividido em funções claras e com responsabilidade única (Single Responsibility Principle), facilitando a manutenção e a leitura.

---

## 🛠️ Funcionalidades Principais

O menu interativo permite ao usuário:

* **1. Adicionar Despesas:** Salva uma nova despesa com `valor` e `categoria`.
* **2. Listar Todas as Despesas:** Exibe todos os registros feitos.
* **3. Mostrar Total de Despesas:** Calcula e exibe a soma de todas as despesas.
* **4. Filtrar por Categoria:** Permite ao usuário buscar e listar apenas despesas de uma categoria específica.
* **5. Sair:** Encerra a aplicação.
* **Interface de Console:** O script utiliza formatação (títulos, linhas) e códigos de cores ANSI (para categorias) para melhorar a experiência do usuário (UX) no terminal.

---

## 🚀 Destaques Técnicos

Este projeto demonstra competência nas seguintes áreas:

* **Programação Funcional:**
    * Uso de `map()` e `lambda` para extrair os valores na função `total_expense`.
    * Uso de `filter()` e `lambda` para buscar itens específicos na função `filter_category`.
* **Estrutura de Dados:**
    * Utilização de **Dicionários** para armazenar cada despesa (`{'amount': ..., 'category': ...}`).
    * Utilização de **Listas** como a estrutura principal para armazenar a coleção de despesas.
* **Modularidade:** O código é organizado em funções (`add_expense`, `show_expenses`, etc.) que são orquestradas pela função `main()`.
* **Tratamento de Erros:** Uso de `try/except` para garantir que a entrada do menu principal seja sempre um número inteiro válido.

---

## 💻 Tecnologias Utilizadas

* **Python 3**
* Módulo Padrão: **`time`** (para a função `sleep()`)

---

## 🏃 Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/KugikiBF/nome-do-seu-repositorio.git](https://github.com/KugikiBF/nome-do-seu-repositorio.git)
    ```

2.  Navegue até o diretório do projeto:
    ```bash
    cd nome-do-seu-repositorio
    ```

3.  Salve o código como um arquivo (ex: `tracker.py`).

4.  **Importante:** Para que o menu interativo inicie, adicione o seguinte "ponto de entrada" (entry point) ao final do seu arquivo `.py`:
    ```python
    if __name__ == "__main__":
        main()
    ```

5.  Execute o script:
    
    ```bash
    python tracker.py
    ```

6.  Siga as opções do menu no terminal.

---

## 👨‍💻 Autor

**Bruno Felipe Mafra Lacerda**

* LinkedIn: [https://www.linkedin.com/in/bruno-felipe-7956bb351/](https://www.linkedin.com/in/bruno-felipe-7956bb351/)
* GitHub: [https://github.com/KugikiBF](https://github.com/KugikiBF)
