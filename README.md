# Chatbot
- Python 中使用 Chatterbot 构建聊天机器人
- Criando Chatbots com Chatterbot em Python
- Building Chatbots with Chatterbot in Python

# Issues
Problemas no uso de uma das bibliotecas
  - time > função clock
    - AttributeError: module 'time' has no attribute 'clock'
    - Problema devido a versão do sqlalchemy
      - Solução: Atualizar o sqlalchemy ou fazer um downgrade do python para uma versão que comporte a função clock
Problema na versão do python
  - ModuleNotFoundError: No module named 'chatterbot'
  - Estamos enfrentando problemas devido a versão do python, a versão sugerida para executar o chartbot está entre a 3.4 e a 3.8
