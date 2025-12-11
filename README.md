# OL Consulting - Plataforma de Gestão e Agendamento Digital

## 📌 Sobre o Projeto
[cite_start]O **OL Consulting** é uma plataforma digital desenvolvida para modernizar e centralizar os canais de atendimento da **Agência Trampo**, uma empresa de marketing digital e desenvolvimento web[cite: 10, 19].

[cite_start]O objetivo principal foi criar uma divisão clara para as consultorias da agência, entregando um **site institucional** integrado a um **sistema de gestão e agendamento de reuniões**, facilitando o contato entre clientes e consultores[cite: 13, 26].

[cite_start]Este projeto foi realizado como parte da disciplina de **Prática de Gestão de Projetos** na FATEC Rubens Lara[cite: 4, 5].

## 🚀 Funcionalidades

* [cite_start]**Site Institucional Responsivo:** Páginas de apresentação (Home), Sobre, Serviços e Contato com identidade visual corporativa e moderna[cite: 118, 524].
* **Sistema de Agendamento:**
    * [cite_start]Agendamento de reuniões com slots de 45 minutos[cite: 550].
    * [cite_start]Painel administrativo para gestão de horários pela equipe da Agência[cite: 547].
    * [cite_start]Integração direta no ambiente WordPress via plugin customizado[cite: 355].
* [cite_start]**Segurança e Performance:** Implementação de HTTPS e otimização para carregamento rápido[cite: 123, 125].

## 🛠 Tecnologias Utilizadas

O projeto passou por uma decisão estratégica de mudança de tecnologias (leia mais na seção "Desafios") para garantir a entrega e estabilidade. A stack final foi:

* [cite_start]**CMS:** WordPress (Tema Flatsome)[cite: 27, 424].
* [cite_start]**Backend/Customização:** PHP (para lógica do plugin de agendamento) e ajustes de servidor[cite: 571, 610].
* [cite_start]**Frontend Customizado:** HTML5 e CSS3 para refinamento de layout e responsividade[cite: 352].
* [cite_start]**Design:** Figma (prototipagem)[cite: 101].
* [cite_start]**Gestão:** Trello (Kanban) para acompanhamento de tarefas[cite: 285].

## 🔄 O "Pivô" Estratégico (Lições Aprendidas)

Um dos maiores diferenciais deste projeto foi a **capacidade de adaptação e gestão de riscos**.

[cite_start]Inicialmente, o projeto foi planejado utilizando **React, Next.js, Node.js e TailwindCSS**[cite: 345]. [cite_start]No entanto, durante a execução, identificamos que a complexidade da integração aliada ao prazo curto (8 semanas) estava gerando riscos críticos ao cronograma[cite: 345, 347].

**A Solução:**
Realizamos uma reunião de alinhamento com o cliente e optamos por migrar a arquitetura para **WordPress + PHP**. Essa decisão permitiu:
1.  [cite_start]Garantir a entrega dentro do prazo (18/11/2025)[cite: 358].
2.  [cite_start]Reduzir bugs críticos de integração[cite: 573].
3.  [cite_start]Facilitar a manutenção futura por parte do cliente[cite: 360].

## 🚧 Desafios de Infraestrutura

[cite_start]Além do desafio de desenvolvimento, enfrentamos um bloqueio de segurança onde o domínio inicial foi categorizado erroneamente em *blacklists* de firewalls (Fortinet)[cite: 737, 753].
* [cite_start]**Resolução:** Atuamos na comunicação com o fornecedor de segurança e realizamos a migração para um novo domínio (`olconsulting.com.br`) para assegurar o acesso dos usuários[cite: 754, 777].

## 👥 Autores

* [cite_start]**Ricardo Panighel Lazarini** [cite: 1]
* [cite_start]**Lucas Silva Fagundes** [cite: 1]

---
[cite_start]*Projeto acadêmico concluído em Novembro de 2025.* [cite: 820]
