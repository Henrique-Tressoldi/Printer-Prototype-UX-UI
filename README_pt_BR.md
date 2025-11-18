# Interface de Equipamento Multifuncional - Projeto Final IHC

Este repositório contém o protótipo de alta fidelidade desenvolvido como Projeto Final para a disciplina de **Interação Humano-Computador (IHC)** na UTFPR.

**Aluno:** Henrique Menezes Tressoldi

## 📋 Sobre o Projeto

O objetivo deste projeto foi projetar e prototipar a interface de um equipamento multifuncional (Impressora, Copiadora e Scanner). O foco principal não foi apenas a estética, mas a aplicação rigorosa de diretrizes de IHC, Engenharia Cognitiva e Semiótica para garantir:

* **Usabilidade:** Facilidade de aprendizado e eficiência de uso.
* **Comunicabilidade:** Clareza na transmissão da lógica do designer para o usuário.
* **Acessibilidade Híbrida:** Interface projetada para ser operada tanto via tela *touch* quanto por painel de botões físicos (simulado na parte inferior da interface).

## 🚀 Funcionalidades e Telas

O protótipo cobre 12 estados críticos do sistema, atendendo a todos os requisitos do edital:

1.  **Menu Principal:** Navegação clara com hierarquia visual.
2.  **Configuração de Impressão:** Seleção de origem (USB, Nuvem) e ajustes rápidos.
3.  **Ajustes de Cópia:** Uso de *sliders* analógicos para densidade e zoom.
4.  **Digitalização:** Fluxos para E-mail, Rede e Pen Drive com memória de preferências.
5.  **Tratamento de Erros (Falta de Papel):** Mensagens construtivas com instruções passo-a-passo.
6.  **Avisos de Segurança:** Bloqueio de operação com tampa aberta (Constraint).
7.  **Feedback de Progresso:** Barras de progresso visuais para operações longas.
8.  **Erros de Conectividade:** Opções de recuperação e caminhos alternativos (Salvar em USB).
9.  **Confirmação de Ações Destrutivas:** Prevenção de cancelamentos acidentais.
10. **Manutenção Preventiva:** Alertas proativos de nível de toner e limpeza.
11. **Configurações Globais:** Acessibilidade, idioma e ajustes de rede.
12. **Histórico de Operações:** Função de "Repetir Tarefa" para eficiência.

## 🧠 Conceitos de IHC Aplicados

O design foi fundamentado nas seguintes categorias de diretrizes:

* **Interação Geral:** Consistência visual, feedback informativo e fácil reversão de ações.
* **Entrada de Dados:** Minimização de ações (uso de *defaults* inteligentes) e prevenção de erros.
* **Exibição de Informações:** Uso de displays analógicos, mensagens de erro significativas e redução da carga de memória.

## 🛠️ Tecnologias

* **HTML5 & CSS3:** Utilizados para criar um layout responsivo e fiel a um painel LCD real.
* **Single-File Component:** Toda a estrutura foi consolidada em um único arquivo para facilitar a visualização sequencial e a captura de telas para o relatório final.

## 📦 Como Visualizar

1.  Baixe o arquivo `multifuncional_final_entrega.html`.
2.  Abra em qualquer navegador web moderno (Chrome, Edge, Firefox).
3.  A visualização apresenta todas as 12 telas em sequência vertical, prontas para análise.

---
*Projeto desenvolvido para a Universidade Tecnológica Federal do Paraná (UTFPR).*
