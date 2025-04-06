# 💰 **Data Pipeline: Extração de Dados Bitcoin com ETL em Python**  

## **Introdução**  

Este projeto é parte de um workshop gratuito de Analista/Cientista/Engenheiro de dados para Iniciantes, com foco no desenvolvimento de pipelines ETL (Extração, Transformação e Carregamento). A proposta é desenvolver um programa que extrai informações de uma API (no caso, a Coinbase), processa esses dados e os armazena em um banco de dados.
Você vai explorar conceitos essenciais da área, como: O funcionamento de APIs e como acessá-las utilizando Python. As etapas de um pipeline ETL: extração, transformação e carregamento.
Métodos para automatizar o processo e garantir a coleta periódica de dados.
No final, você terá criado um sistema capaz de:
Obter em tempo real a cotação atual do Bitcoin.
Armazenar essas informações em formato estruturado para posterior análise.

### **Etapas do Projeto**  

1. **Extração (E)**:  
   - Utilizar a **API da Coinbase** para obter o preço atual da Bitcoin.  
   - Trabalhar com os endpoints públicos da API (sem necessidade de autenticação).  

2. **Transformação (T)**:  
   - Selecionar apenas as informações relevantes: preço da Bitcoin, horário da consulta e moeda de referência (USD).  
   - Organizar os dados no formato tabular utilizando **Pandas**.  

3. **Carga (L)**:  
   - Armazenar os dados coletados em um arquivo **CSV** ou em um banco de dados SQLite.  

4. **Automatização**:  
   - Agendar o programa para executar periodicamente (por exemplo, a cada hora ou diariamente), garantindo a coleta contínua dos dados.  

---

## **Tecnologias Utilizadas**  
- **Python 3.12**  
- **Bibliotecas**:  
   - `requests`: Para consumir APIs.  
   - `pandas`: Para manipulação e organização de dados.  
   - `sqlite3`: Para armazenamento em banco de dados (opcional).  
   - `tinydb`: Para armazenamento em banco de dados NoSQL.
   - `sqlalchemy`: SQLAlchemy é uma biblioteca de mapeamento objeto-relacional para Python.
   - `psycopg2-binary`: Psycopg é uma biblioteca de acesso a dados PostgreSQL para Python.
   - `streamlit`: Para criar dashboards interativos.
   - `time`: Para medir o tempo de execução do programa.
   - `datetime`: Para manipulação de datas e horas.
- **Coinbase API**: Para obter o preço da Bitcoin em tempo real.  

