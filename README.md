# Guia Interativo da Diretiva NIS2 em Portugal

Este repositório contém uma aplicação web interativa de página única (SPA) concebida para facilitar a compreensão e exploração da Diretiva NIS2 (UE 2022/2555) e o seu estado de transposição em Portugal. O objetivo é tornar a informação complexa sobre cibersegurança mais acessível e envolvente para os utilizadores.

## Descrição

A aplicação "Guia Interativo da Diretiva NIS2 em Portugal" traduz um relatório detalhado sobre a NIS2 num formato web intuitivo. Permite aos utilizadores navegar por diferentes aspetos da diretiva, incluindo o seu contexto, o processo de transposição em Portugal, as entidades abrangidas, os requisitos de segurança, as sanções e os desafios/oportunidades.

## Funcionalidades

* **Visão Geral da NIS2:** Contexto e importância estratégica da diretiva.

* **Cronologia de Transposição:** Linha do tempo visual dos marcos legislativos em Portugal.

* **Expansão do Âmbito:** Gráfico interativo que ilustra o aumento do número de entidades reguladas.

* **Ferramenta de Autoavaliação:** Um formulário para ajudar as entidades a determinar a sua possível classificação (Essencial ou Importante) com base em critérios de setor e tamanho.

* **Medidas Mínimas de Segurança:** Lista de requisitos de segurança apresentada num formato de acordeão expansível.

* **Prazos de Notificação de Incidentes:** Gráfico que visualiza os prazos para a notificação de incidentes significativos.

* **Regime Sancionatório:** Informação dinâmica sobre as coimas máximas e outras sanções aplicáveis a Entidades Essenciais e Importantes.

* **Desafios e Oportunidades:** Análise dos principais obstáculos e benefícios da implementação da NIS2.

* **Recomendações:** Próximos passos práticos para as organizações iniciarem a sua jornada de conformidade.

* **Design Responsivo:** Otimizado para visualização em dispositivos móveis, *tablets* e *desktops*.

## Tecnologias Utilizadas

* **HTML5:** Estrutura da página.

* **Tailwind CSS:** Framework CSS para estilização e responsividade.

* **Chart.js:** Biblioteca JavaScript para a criação de gráficos dinâmicos (Canvas).

* **JavaScript (Vanilla JS):** Para a lógica de interação, manipulação do DOM e gestão do estado da aplicação.

## Como Usar

Para visualizar e interagir com esta aplicação, siga estes passos simples:

1.  **Clone o repositório** (ou faça o download do ficheiro `nis2-guia.html`).

2.  **Abra o ficheiro `nis2-guia.html`** no seu navegador web preferido (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.).

Como é uma aplicação de página única e não requer um servidor *backend*, pode ser executada diretamente a partir do seu sistema de ficheiros local.

## Estrutura do Projeto

O projeto consiste num único ficheiro HTML (`nis2-guia.html`) que contém todo o HTML, CSS (via CDN do Tailwind) e JavaScript.

## Considerações para o SharePoint Online

Embora esta aplicação seja um ficheiro HTML autónomo, a sua instalação direta no SharePoint Online através da *Web Part* "Incorporar" (`Embed`) pode ter limitações devido às políticas de segurança do SharePoint (como a Política de Segurança de Conteúdo - CSP) e ao comportamento dos *iframes*. Algumas funcionalidades interativas JavaScript podem ser bloqueadas ou não funcionar como esperado.

Para uma integração mais robusta e segura no SharePoint Online, a abordagem recomendada é desenvolver uma *Web Part* personalizada utilizando o **SharePoint Framework (SPFx)**. O SPFx permite a criação de componentes que se integram nativamente e de forma segura com o ambiente do SharePoint.

## Licença

Este projeto é de código aberto e está disponível sob a licença [MIT License](LICENSE).

---

**Nota:** Esta aplicação é apenas para fins informativos e não constitui aconselhamento jurídico ou profissional. Consulte sempre as autoridades competentes (como o CNCS em Portugal) e aconselhamento especializado para questões de conformidade com a NIS2.
