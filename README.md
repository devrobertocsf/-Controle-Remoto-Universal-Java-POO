# Controle Remoto Universal Java -POO
Este projeto simula o funcionamento de um controle remoto, desenvolvido para aplicar os conceitos de Encapsulamento e Interfaces em Java. O código segue o padrão de "Contratos", onde a interface define as ações possíveis e a classe as implementa de forma protegida.

---

## Interfaces: 
Uso do contrato Controlador para definir métodos abstratos.

## Encapsulamento Total: 
Atributos e métodos acessores (getters/setters) definidos como private, impedindo o acesso externo indevido.

## Sobrescrita de Métodos (@Override): 
Implementação real das ações definidas na interface.

## Lógica de Proteção:
Regras de negócio que impedem ações impossíveis (ex: aumentar volume com a TV desligada).

# 🛠️ Funcionalidades
O sistema permite realizar as seguintes operações através da interface:

Ligar / Desligar: Altera o estado de energia do dispositivo.

Controle de Volume: Aumentar, diminuir ou ativar o mudo (com indicadores visuais no console).

Controle de Reprodução: Funções de Play e Pause.

Menu Interativo: Exibição do status atual do dispositivo e barra de volume gráfica [].

# 📂 Estrutura do Projeto
Controlador.java: Interface que contém a assinatura de todos os métodos abstratos.

ControleRemoto.java: Classe que implementa a interface e contém a lógica interna.

aula06principal.java: Classe principal para execução e testes do objeto.

---

Projeto desenvolvido como parte dos meus estudos de Java POO, focado em boas práticas e arquitetura de software.

---
