# Leitura e Normalização de Arquivos JSON com Pandas

Este projeto tem como objetivo colocar em prática os conhecimentos adquiridos nas aulas da instrutora **[Valquíria Alencar](https://github.com/vqrca), instrutora da [Alura](https://www.alura.com.br/)**, do curso  *Pandas I/O: Trabalhando com diferentes formatos de arquivos trabalhando com diferentes formatos de arquivos/ Manipulando arquivos Jason*. O foco desta aula específica foi trabalhar com **dados em formato JSON** oriundos de uma API.

---

## Objetivo

Demonstrar como:

- Acessar uma **API REST** que retorna dados no formato **JSON**;
- Utilizar as bibliotecas **`requests`** e **`json`** para extrair os dados da web;
- Transformar os dados JSON em um **DataFrame** com a biblioteca **`pandas`**;
- **Normalizar** estruturas aninhadas (nested structures) usando `pd.json_normalize`;
- Realizar uma análise exploratória simples das informações extraídas;
- Exportar os dados para formatos como **CSV**, **Excel** e **JSON**.

---

## Tecnologias Utilizadas

- Python 
- pandas
- requests
- json
- Google Colab 
- API: [JSONPlaceholder](https://jsonplaceholder.typicode.com/users)
- Dados extras: [pacientes.json - GitHub Alura](https://github.com/alura-cursos/Pandas/blob/main/pacientes.json)

---

## Fonte dos Dados

Para fins didáticos, foi utilizada a API pública **[JSONPlaceholder](https://jsonplaceholder.typicode.com/users)**, que retorna uma lista de usuários fictícios com informações como nome, e-mail, localização e empresa. Também foram utilizados dados complementares de pacientes fornecidos pela própria Alura:

📎 `https://github.com/alura-cursos/Pandas/blob/main/pacientes.json`

---

## Etapas Realizadas

1. **Requisição de dados** via `requests.get()` da API.
2. Conversão do conteúdo JSON para estrutura de dicionário Python (`.json()`).
3. Normalização de campos aninhados com `pd.json_normalize()`.
4. Análise preliminar:
   - Verificação de colunas e tipos de dados;
   - Análise estatística descritiva de colunas numéricas;
   - Extração de colunas de geolocalização para análise geográfica básica.
5. Exportação dos dados para os seguintes formatos:
   - `.csv`
   - `.xlsx`
   - `.json`
6. Simulação de upload de arquivos locais no ambiente do **Google Colab**.

---

## Resultados

- Os dados brutos foram transformados em um **DataFrame estruturado** e pronto para análise.
- A extração de informações geográficas possibilitou uma primeira análise espacial (nomes, cidades, coordenadas).
- Os dados foram exportados com sucesso em múltiplos formatos, possibilitando sua integração com outras ferramentas e processos de negócio.

---

## Aprendizados

Este exercício permitiu consolidar os seguintes conceitos fundamentais para quem trabalha com Ciência de Dados:

- Entendimento da estrutura de dados JSON;
- Comunicação com APIs REST;
- Transformação de dados semi-estruturados em tabelas analíticas;
- Boas práticas de extração, transformação e carga (ETL) com a biblioteca pandas.

---

## Referência Didática

- Plataforma: [Alura](https://www.alura.com.br)
- Curso: *Pandas I/O: Trabalhando com diferentes formatos de arquivos trabalhando com diferentes formatos de arquivos/ Manipulando arquivos Jason*
- Instrutora: [Valquíria Alencar](https://github.com/vqrca)
---

## Licença

Este projeto teve como objetivo aprendizagem pessoal.

---
