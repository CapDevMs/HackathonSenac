# 🚑 **SAMU System Redesign** - *Hackathon Senac Decola*

📢 **Problema:**
Atualmente, a Secretaria Municipal de Saúde utiliza o **e-SUS Samu**, um sistema descontinuado desde 2018 pelo Ministério da Saúde. O objetivo do nosso projeto é modernizar essa solução para melhorar a eficiência, comunicação e rapidez no atendimento de emergências médicas.

---

## 📖 **Sobre o Projeto**

Nosso sistema foi projetado para transformar a experiência do Serviço de Atendimento Móvel de Urgência (**SAMU**), com foco em:
- **Agilidade no atendimento telefônico (192)**.
- **Gestão eficiente da frota e das ocorrências.**
- **Monitoramento em tempo real das ambulâncias.**
- **Compatibilidade com dispositivos móveis.**
- **Painéis intuitivos e relatórios detalhados.**

---

## 🎯 **Requisitos do Sistema**

### 🚦 **Tipos de Usuários**
1. **TARM** (*Técnico Auxiliar de Regulação Médica*):
   - Registra dados das ocorrências e auxilia no encaminhamento médico.

2. **Rádio Operador**:
   - Opera sistemas de radiocomunicação, gerencia a frota e registra a movimentação das viaturas.

3. **Médico Regulador**:
   - Avalia e classifica as ocorrências, designando equipes de atendimento.

4. **Equipe de Atendimento/Ambulância**:
   - Realiza o atendimento in loco, registrando procedimentos médicos.

---

## 💻 **Funcionalidades do Sistema**

### 🔗 **TARM**
- Registro de dados da ocorrência:
  - Número telefônico, nome do solicitante, motivo da ligação, tipo e origem da ocorrência.
- Localização detalhada:
  - Município, bairro, rua, número, complemento e ponto de referência.

### 🩺 **Médico Regulador**
- Classificação de prioridade (verde, amarelo, vermelho).
- Avaliação médica e designação de equipes.

### 📡 **Rádio Operador**
- Status em tempo real das viaturas:
  - **Ocorrências em aberto**.
  - **Ocorrências em atendimento**.
  - **Geolocalização das viaturas**.
  - **Equipes disponíveis**.

### 🚨 **Equipe de Atendimento/Ambulância**
- Acesso móvel:
  - Consulta e atualização dos dados da ocorrência via dispositivos móveis.
- Registro de procedimentos médicos realizados.

### 📊 **Dashboards e Relatórios**
- Painéis intuitivos para visualização rápida das informações.
- Emissão de relatórios detalhados.

### 🌍 **Georreferenciamento**
- Monitoramento do deslocamento em tempo real.
- Status das viaturas:
  - **Livre**, **em ocorrência**, **em manutenção**.

---

## 📱 **Compatibilidade**
- Totalmente responsivo.
- Compatível com dispositivos móveis e desktops.

---

## 🚀 **Tecnologias Utilizadas**
- **Frontend**: TailwindCSS, Javascript
- **Backend**: PHP, Python
- **Banco de Dados**: MySQL
- **Geolocalização**: Google Maps API
- **Hospedagem**: AWS

---

## 👥 **Equipe**
| Nome                  |
|-----------------------|
| Felipe Braiani        |
| Anna Lorena Napoleão Campos       |
| Rafael Montiel   |
| Rafaela Vergotti   |
| Filipe Simões   |
| João Gabriel   |

---

## 🎉 **Contribuindo**
1. Faça um fork do projeto.
2. Crie uma branch para a sua feature: `git checkout -b minha-feature`.
3. Faça um commit: `git commit -m 'Minha nova feature'`.
4. Envie sua feature: `git push origin minha-feature`.

---

## 🌟 **Apoio e Agradecimentos**
Este projeto foi desenvolvido durante o **Hackathon Senac Decola**. Agradecemos a todos os mentores, organizadores e colegas participantes pela colaboração!

*🩺 Porque cada segundo importa, e vidas estão em jogo!*
