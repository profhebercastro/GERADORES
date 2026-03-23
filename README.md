# 📑 Checklist de Manutenção de Geradores - USP CeTI-RP

Este projeto é uma ferramenta web simplificada e eficiente desenvolvida para a automação da vistoria preventiva e corretiva dos grupos geradores do **Centro de Tecnologia da Informação de Ribeirão Preto (CeTI-RP) - USP**.

A interface foi construída em HTML5 e Bootstrap 5, integrada ao **Google Forms** para atuar como backend de recebimento de dados e ao **Google Sheets** para o armazenamento e auditoria das vistorias.

---

## 🚀 Link do Projeto
Acesse o formulário em tempo real:
👉 [**Checklist Geradores CeTI-RP**](https://profhebercastro.github.io/GERADORES/)

---

## ⚙️ Equipamentos Monitorados

O sistema atende aos dois grupos geradores da unidade:
1.  **Gerador Cummins:** MOTOR MODELO CUMMINS 4BTA G4 - GERADOR STAMFOR 85/93 KVA.
2.  **Gerador Stemac:** MOTOR MODELO MWM D229-4 - GERADOR WEG 48/54 KVA.

## ✨ Principais Funcionalidades

*   **📱 Design Responsivo (Mobile-First):** Otimizado para smartphones, permitindo que o técnico realize a vistoria diretamente no local dos equipamentos.
*   **🚨 Alarme de Nível Crítico:** O campo de combustível possui uma lógica em JavaScript que dispara um alerta visual (cor vermelha e animação piscante) caso o volume informado seja inferior a **70 Litros**.
*   **🛠️ Gestão de Atividades:** Permite selecionar o tipo de intervenção:
    *   **Vistoria Semanal Preventiva:** Rotina de verificação de níveis e funcionamento.
    *   **Manutenção Semestral:** Registro de trocas de óleo lubrificante e filtros.
    *   **Conserto / Manutenção Corretiva:** Registro de reparos de defeitos (com aviso inteligente para detalhamento no campo de observações).
*   **📩 Envio em Segundo Plano:** Utiliza um `iframe` oculto para processar os dados, mantendo o usuário na página e exibindo uma mensagem de sucesso customizada.

## 🛠️ Tecnologias Utilizadas

*   **Frontend:** HTML5, CSS3, JavaScript (ES6+).
*   **Framework:** [Bootstrap 5.3](https://getbootstrap.com/).
*   **Backend:** Integração via POST com Google Forms.
*   **Banco de Dados:** Google Sheets (Planilha de respostas).
*   **Hospedagem:** GitHub Pages.

## 🎨 Identidade Visual (Padrão USP)

O layout foi desenvolvido respeitando as cores institucionais da Universidade de São Paulo:
- **Amarelo USP:** `#f7b22a`
- **Azul USP:** `#005596`
- **Tech Turquesa:** `#03b6c1` (Cor de destaque para botões e seções técnicas)

## 📂 Estrutura de Arquivos

*   `index.html`: Arquivo principal com toda a estrutura, estilos e lógica.
*   `logo.png`: Logotipo oficial da USP CeTI-RP utilizado no banner.
*   `README.md`: Documentação do projeto.

---
**Desenvolvido para o CeTI-RP - Superintendência de Tecnologia da Informação**
**Universidade de São Paulo**