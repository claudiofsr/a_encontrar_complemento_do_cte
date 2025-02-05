# a_encontrar_complemento_do_cte
Este programa busca informações de chaves CTes em documentos fiscais de formato xml.

Em seguida, retém as chaves complementares dos CTes no arquivo:

* <transporte_subcontratado-chaves_complementares_dos_CTes.txt>

# Encontrando o Complemento do CTe (Conhecimento de Transporte Eletrônico)

Este projeto Rust fornece uma ferramenta simples para encontrar complementos de CTe (Conhecimento de Transporte Eletrônico).

## O que é um CTe?

O Conhecimento de Transporte Eletrônico (CTe) é um documento fiscal digital, utilizado no Brasil para acobertar operações de transporte de cargas.

## Como Usar

1.  **Certifique-se de ter o Rust instalado:** Se você ainda não tem o Rust, siga as instruções em [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).

2.  **Clone o repositório:**
    ```bash
    git clone https://github.com/claudiofsr/a_encontrar_complemento_do_cte.git
    cd a_encontrar_complemento_do_cte
    ```

3.  **Compile e instale o projeto:**
    ```bash
    cargo build --release && cargo install --path=.
    ```

4.  **Execute o programa:**
    Em um diretório contendo arquivos de CTe em formato XML, execute:
    ```bash
    a_encontrar_complemento_do_cte
    ```
