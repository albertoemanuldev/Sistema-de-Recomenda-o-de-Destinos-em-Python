# Sistema de Recomendação de Viagens

Este projeto é um sistema simples de recomendação de destinos turísticos no Brasil, baseado nas preferências do usuário quanto a clima, ambiente e orçamento.

## Curso: Fundamentos de Python para IA - SENAI
Projeto didático para prática de lógica de programação e manipulação de dados em Python. 

## Estrutura dos Arquivos

- **main.py**  
  Arquivo principal. Executa o sistema, interage com o usuário e exibe o destino recomendado.

- **dados.py**  
  Contém a base de dados dos destinos turísticos, com informações sobre clima, ambiente, orçamento e justificativa para recomendação.

- **sistema.py**  
  Implementa as funções de interação com o usuário (coleta de preferências) e de busca do destino compatível.

## Como usar

1. Certifique-se de que todos os arquivos (`main.py`, `dados.py`, `sistema.py`) estejam na mesma pasta.
2. Execute o arquivo principal:
   ```sh
   python main.py
3.Responda às perguntas sobre suas preferências de clima, ambiente e orçamento.
4.O sistema irá sugerir um destino que melhor se encaixa no seu perfil.

# Exemplo de uso:
--- Sistema de Recomendação de Viagens ---
Olá! Vamos encontrar o destino perfeito para você.
Você prefere clima quente ou frio? quente
Prefere lugares com natureza ou paisagens urbanas? (digite 'natureza' ou 'urbano') natureza
Qual é o seu orçamento disponível? (baixo, medio, alto) alto

Buscando um destino com base nas suas preferências...

Destino recomendado encontrado!
Nome: Maceió (AL)
Justificativa: Um paraíso ecológico com as praias mais bonitas do Brasil, ideal para quem busca natureza exuberante.
