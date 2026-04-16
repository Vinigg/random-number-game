# 🎯 Jogo de Adivinhação de Número em C

<div align="center">

![C](https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![Disciplina](https://img.shields.io/badge/Disciplina-FDS-orange?style=for-the-badge)
![Universidade](https://img.shields.io/badge/Projeto-Faculdade-purple?style=for-the-badge)

</div>

---

## 📋 Sobre o Projeto

Este projeto é um **Jogo de Adivinhação de Número Aleatório** desenvolvido em linguagem C, como parte de um projeto interdisciplinar envolvendo múltiplas matérias do curso.

O jogo consiste em tentar adivinhar um número gerado aleatoriamente pelo sistema dentro de um intervalo definido. O jogador recebe dicas sobre se o seu palpite foi maior ou menor que o número secreto, até acertá-lo ou esgotar as tentativas disponíveis.

### 🎮 Funcionalidades Principais

- Menu interativo com opções de jogo
- Geração de número aleatório
- Feedback a cada tentativa (maior/menor)
- Limite de tentativas configurável
- Registro de recordes (High Score)
- Estatísticas de desempenho
- Persistência de dados entre sessões
- Tratamento robusto de erros de entrada
- Reinicialização de partida

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** C
- **Compilador:** Compatível com compiladores C11
- **Gerenciamento de Build:** Makefile
- **Controle de Versão:** Git / GitHub

---

## 📁 Estrutura do Projeto

```
jogo-adivinhacao/
├── src/
│   ├── main.c           # Ponto de entrada e menu principal
│   ├── game.c           # Lógica central do jogo
│   ├── score.c          # Sistema de pontuação e recordes
│   ├── stats.c          # Estatísticas agregadas
│   ├── utils.c          # Funções utilitárias e recursão
│   └── io.c             # Tratamento de entrada/saída
├── include/
│   ├── game.h
│   ├── score.h
│   ├── stats.h
│   └── utils.h
├── data/
│   └── scores.dat       # Arquivo de persistência
├── Makefile
└── README.md
```

---

## 👥 Equipe e Responsabilidades

| Integrante | Papel | Histórias de Usuário |
|---|---|---|
| **Vinicius Pessoa de Albuquerque** | Tech Lead / Arquiteto | [UH3] Ciclo de Jogo com Feedback · [UH10] Cálculos Base (Recursão) |
| **Pedro Pessoa de Albuquerque Neto** | Desenvolvedor / QA | [UH8] Tratamento de Erros |
| **Roberto Henrique Cavalcanti Freitas** | Desenvolvedor Back-end | [UH7] Persistência de Dados · [UH11] Recorde Local (High Score) |
| **Saulo Eduardo Almeida dos Santos** | Desenvolvedor | [UH12] Estatísticas Agregadas |
| **Thayna Vercosa de Andrade** | Desenvolvedora / Product Owner | [UH6] Limite de Tentativas |
| **Thiago Cardozo da Conceição** | Desenvolvedor / Analista | [UH13] Heurística de Estratégia |
| **Vinicius Wagner Gomes Germano** | Desenvolvedor Full Stack | [UH1] Interface Principal (Menu) · [UH2] Geração de Número |
| **Vitoria Gabrielly Gomes da Silva** | Desenvolvedora / QA | [UH5] Condição de Vitória | 
| **Wesley Yuri da Silva** | Desenvolvedor / Analista | [UH9] Reinicialização · [UH14] Leitura e Parsing do Histórico |
| **Yasmin Karolina Silva de M. Godinho** | Desenvolvedora / QA | [UH4] Palpite Básico |

---

## 📊 Quadro de Atividades / Backlog (Kanban)

<div align="center">

<!-- ✅ SUBSTITUA A LINHA ABAIXO PELO PRINT DO QUADRO -->
<img width="1913" height="964" alt="image" src="https://github.com/user-attachments/assets/3bd919ed-8366-46d0-a0b0-fee3c7881860" />

*Print do quadro de atividades da equipe — atualizado em: `09/04/2026`*

</div>
---
## Protótipo de Baixa Fidelidade
<div align="center">
  <img width="1600" height="742" alt="image" src="https://github.com/user-attachments/assets/da304619-05c3-4cac-b06d-e33b453837b7" />
  
  *Print do protótipo de baixa fidelidade do Figma — atualizado em: `16/04/2026`*
</div>
---
## 🚀 Como Compilar e Executar

### Pré-requisitos

- GCC instalado (ou um compilador equivalente)  
- Sistema operacional: Linux, macOS ou Windows (com MinGW)

### Compilação

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/jogo-adivinhacao.git
cd jogo-adivinhacao

# Compilar com Makefile
make

# Ou compilar manualmente
gcc src/*.c -o jogo -Wall -Wextra -std=c99
```

### Execução

```bash
./jogo
```

---

## 📜 Licença

Este projeto foi desenvolvido para fins acadêmicos. Todos os direitos reservados aos integrantes da equipe.

---

<div align="center">

Desenvolvido com 💻 pela equipe · Projeto Interdisciplinar · 2025

</div>
