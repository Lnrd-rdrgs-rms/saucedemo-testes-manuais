# Projeto de Testes Funcionais Manuais — SauceDemo

## 1. Sobre o projeto

Este projeto tem como objetivo demonstrar a aplicação de conceitos de Quality Assurance (QA) por meio de testes funcionais manuais na aplicação [SauceDemo](https://www.saucedemo.com/).

O trabalho contempla o planejamento dos testes, a elaboração e execução de casos de teste, o registro de defeitos, a coleta de evidências e a elaboração de um relatório final.

## 2. Objetivo

Validar os principais comportamentos da aplicação, comparando os resultados obtidos durante a execução com os resultados esperados definidos nos casos de teste.

## 3. Escopo dos testes

Foram abordadas as seguintes funcionalidades:

- **Autenticação:** acesso com credenciais válidas, inválidas e não preenchidas.
- **Produtos:** adição de produtos ao carrinho, apresentação das informações e ordenação por preço.
- **Carrinho:** remoção de produtos, atualização do contador de itens e retorno ao catálogo.

### 3.1. Fora do escopo

- Finalização da compra (checkout).
- Testes de API.
- Testes de desempenho.
- Testes de segurança.
- Testes de acessibilidade.
- Testes automatizados.

## 4. Ambiente de testes

- **Aplicação:** SauceDemo.
- **Tipo de teste:** funcional manual.
- **Sistema operacional:** Windows 11.
- **Navegador:** Google Chrome.
- **Dispositivo:** notebook.

## 5. Resultados da execução

Foram executados nove casos de teste, com os seguintes resultados:

| Resultado | Quantidade | Percentual |
|---|---:|---:|
| Aprovados (PASS) | 8 | 88,9% |
| Reprovados (FAIL) | 1 | 11,1% |
| Não executados | 0 | 0% |
| **Total executado** | **9** | **100%** |

## 6. Defeito identificado

Durante a execução, foi identificado um problema na apresentação da descrição do produto **Sauce Labs Backpack**.

- **Identificação:** BUG-001.
- **Caso de teste relacionado:** TC-005.
- **Descrição:** a descrição do produto apresenta a expressão `carry.allTheThings()`, que aparenta ser sintaxe de código e pode prejudicar a clareza das informações exibidas.
- **Severidade:** Baixa.
- **Prioridade:** Média.
- **Status:** Enviado para correção.

A evidência do defeito foi registrada e armazenada junto aos materiais do projeto. A correção ainda não foi confirmada por meio de um novo teste.

## 7. Documentação do projeto

O repositório reúne os documentos produzidos durante o projeto:

- [Plano de testes](01-planejamento/)
- [Casos de teste](02-casos-de-teste/Casos-de-Teste_SauceDemo.xlsx)
- [Resumo da execução](03-execucao/)
- [Registro de defeitos](04-defeitos/Registro-de-Defeitos-SauceDemo.xlsx)
- [Evidências de teste](05-evidencias/)
- [Relatório final](06-relatorio-final/Relatorio-de-Execucao-SauceDemo.pdf)

## 8. Aprendizados e competências demonstradas

- Planejamento e execução de testes funcionais manuais.
- Elaboração e documentação de casos de teste.
- Comparação entre resultados esperados e obtidos.
- Registro e classificação de defeitos.
- Organização de evidências e documentação de QA.
- Utilização do GitHub para apresentação de um projeto de portfólio.

## 9. Considerações finais

O projeto permitiu aplicar práticas fundamentais de QA em uma aplicação web, desde a definição do escopo até a documentação dos resultados.

Os resultados apresentados estão limitados às funcionalidades e aos casos de teste executados. Portanto, não representam uma garantia de ausência de outros defeitos na aplicação.
