# 🛠️ Mariano — Montador de Móveis | Landing Page & Simulador de Orçamento

> *Uma solução web moderna, responsiva e focada em conversão para apresentação de serviços e geração de orçamentos via WhatsApp.*

---

## 🎯 Sobre o Projeto & Motivação

Este projeto nasceu de um gesto de **gratidão**. Após contratar o **Mariano** para um serviço de montagem de móveis e constatar a excelência, o cuidado e o preço justo do trabalho prestado, decidi desenvolver esta *Landing Page* institucional como forma de retribuir.

O objetivo principal é ajudar a impulsionar o negócio local do profissional, oferecendo a ele uma presença digital moderna, profissional e otimizada para captar novos clientes na região de Campinas, Hortolândia, Sumaré e entorno.

---

## 🚀 Funcionalidades

- **Design Dark & Moderno:** Interface visual com tipografia marcante (`Outfit` e `Inter`) e paleta de cores temática.
- **Simulador / Formulário Dinâmico de Orçamento:** O cliente seleciona o tipo de serviço, os móveis necessários, digita a localização e observações.
- **Integração Direta com WhatsApp:** Ao enviar o formulário, os dados são formatados automaticamente e abrem uma conversa pronta no WhatsApp do profissional.
- **Layout Totalmente Responsivo:** Otimizado para navegação em dispositivos móveis (smartphones) e desktops.
- **Botão Flutuante (CTA Direct):** Acesso rápido ao contato a qualquer momento durante a rolagem da página.
- **SEO Base:** Meta tags configuradas para buscas locais na região de atuação.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** (Estruturação semântica)
- **Tailwind CSS** (Estilização responsiva e utilitária via CDN)
- **JavaScript (Vanilla)** (Lógica do formulário e conversão de dados para URL do WhatsApp)
- **FontAwesome** (Iconografia temática)
- **Google Fonts** (Tipografia: *Outfit* e *Inter*)

---

## 📱 Como Funciona o Envio de Orçamento

1. O cliente preenche o nome, localização e tipo de serviço.
2. Marca as opções de móveis que deseja montar/desmontar.
3. Ao clicar em **"Enviar para o WhatsApp"**, o script JavaScript captura os dados e gera uma mensagem estruturada no seguinte formato:

```text
Olá Mariano! Gostaria de um orçamento:

*Nome:* João Silva
*Local:* Centro - Campinas
*Serviço:* Montagem de Móveis Novos
*Móveis:* Guarda-Roupa, Painel de TV / Rack
*Obs:* Móvel novo na caixa de 6 portas.
