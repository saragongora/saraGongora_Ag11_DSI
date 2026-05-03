# saraGongora_Ag11_DSI

# Controle de Níveis de Água

## Sobre o projeto

Este projeto foi desenvolvido para a **Agenda 11** da disciplina **Desenvolvimento de Sistemas I**.

O sistema simula o monitoramento de um reservatório de água por meio do terminal, exibindo mensagens coloridas conforme o nível de água identificado.

Para melhorar a visualização das informações, foi utilizada a biblioteca **Colorama**, permitindo representar cada nível com uma cor específica.

---

## Funcionalidades

* Simulação de 5 níveis de água do reservatório
* Exibição de mensagens coloridas no terminal
* Utilização de listas para armazenamento dos níveis
* Uso de função para definição das cores
* Restauração automática do estilo padrão do terminal

---

## Tecnologias utilizadas

* Python
* Biblioteca Colorama

---

## Como executar

### 1. Instale a biblioteca necessária

```bash
pip install colorama
```

### 2. Execute o programa

```bash
python controleAgua.py
```

---

## Estrutura do sistema

O programa trabalha com cinco níveis:

* Nível 1 — Muito baixo (crítico)
* Nível 2 — Baixo
* Nível 3 — Médio
* Nível 4 — Alto
* Nível 5 — Muito alto (alerta)

Cada nível é exibido com uma cor específica para facilitar a identificação da situação do reservatório.

---

## Objetivo acadêmico

Aplicar conceitos estudados em sala, como:

* Listas
* Funções
* Bibliotecas externas
* Organização de código
* Simulação de sistemas reais em terminal
