# Snippets para Gherkin em pt-br

Snippets para autocomplete no Gherkin em pt-br. O suporte é para arquivos com a extensão `.feature`.

<img src="https://raw.githubusercontent.com/samuel0072/vscode-feature-snippets/main/images/snippets.gif" alt="Exemplo de uso"/>


Essa extensão tem os seguintes snippets disponíveis:

- `Cenário` e `cnr`:

    ```gherkin
    Cenário: 
        Dado 
        Quando 
        Então 
    ```

- `Esquema` e `esqcnr`:

    ```gherkin
    Esquema do Cenário: 
        Dado 
        Quando 
        Então 

        Exemplos:
        ||
    ```

- `Contexto` e `ctx`:

    ```gherkin
    Contexto: 
        Dado 
    ```

- `Funcionalidade` e `fnc`:

    ```gherkin
    Funcionalidade: 
        Como 
        Gostaria 
        Para 
    ```

- `fcc`:

    ```gherkin
    Funcionalidade: 
        Como 
        Gostaria 
        Para 

        Contexto: 
            Dado 

        Cenário: 
            E 
            Quando 
            Então 
    ```

- `cdc`:

    ```gherkin
    Cenário: 
        E 
        Quando 
        Então 
    ```

- `csc`:

    ```gherkin
    Cenário: 
        Quando 
        Então 
    ```