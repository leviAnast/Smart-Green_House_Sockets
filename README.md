# Sistema de Monitoramento e Controle de Estufa

Este é um sistema de monitoramento e controle de estufas automatizado, desenvolvido em Python, utilizando sockets para comunicação entre as entidades envolvidas: **Gerenciador**, **Sensores**, **Atuadores** e **Cliente**. Este sistema permite o monitoramento e controle dos parâmetros da estufa, como **temperatura**, **umidade** e **nível de CO2**.

## Funcionalidades

- **Gerenciador:** Centraliza a comunicação entre sensores, atuadores e clientes, gerenciando os parâmetros e acionando os atuadores conforme necessário.
- **Sensores:** Monitoram continuamente os níveis de temperatura, umidade e CO2 e enviam leituras para o gerenciador.
- **Atuadores:** Recebem comandos do gerenciador e podem ser ativados ou desativados para ajustar os parâmetros da estufa.
- **Cliente:** Interface de usuário que permite a visualização dos dados dos sensores, o status dos atuadores e a alteração dos parâmetros da estufa.

## Estrutura do Projeto

O projeto está dividido nos seguintes módulos principais:

1. **Gerenciador**: Responsável por gerenciar as conexões, armazenar o estado dos sensores e atuadores e realizar o controle automatizado de acordo com os parâmetros definidos.

2. **Cliente**: Interface que permite o usuário monitorar os sensores e modificar os parâmetros da estufa.

3. **Sensores**: Monitoram os dados ambientais (temperatura, umidade e CO2) e enviam leituras ao gerenciador.

4. **Atuadores**: Dispositivos que alteram as condições da estufa com base em comandos do gerenciador.
