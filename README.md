DOCUMENTO DE REQUISITOS DE SOFTWARE
INSTITUTO FEDERAL DE PERNAMBUCO – CAMPUS PALMARES
CURSO TÉCNICO INTEGRADO EM INFORMÁTICA PARA INTERNET
DISCIPLINA: LINGUAGEM DE TÉCNICA DE PROGRAMAÇÃO 2 (LTP2)


Sistema: Site Informativo Corinthians Monte


Discentes:
Angélica Benigno de Vasconcelos
Laura Fernanda Galdino Ramos

Docente:
Carlos Fernandes




Local: Palmares – PE
5 de maio de 2026

SUMÁRIO
DOCUMENTO DE REQUISITOS DE SOFTWARE	1
SUMÁRIO	2
1. PREFÁCIO	3
2. INTRODUÇÃO	4
3. GLOSSÁRIO	5
4. DEFINIÇÃO DE REQUISITOS DO USUÁRIO	6
5. ARQUITETURA DO SISTEMA	7
6. ESPECIFICAÇÃO DE REQUISITOS DO SISTEMA	8
7. MODELOS DE SISTEMA	9
8. EVOLUÇÃO DO SISTEMA	10
9. APÊNDICES	11

1. PREFÁCIO
Este documento apresenta a especificação de requisitos do sistema “Site Informativo Corinthians Monte”, desenvolvido como atividade da disciplina Linguagem de Técnica de Programação 2. O objetivo é estabelecer uma descrição clara e organizada das funcionalidades e restrições do sistema, servindo como base para seu desenvolvimento e avaliação.


2. INTRODUÇÃO
2.1 Objetivo
Este documento tem como finalidade descrever os requisitos do sistema, garantindo entendimento comum entre desenvolvimento e avaliação.
2.2 Escopo
O sistema consiste em um site estático desenvolvido exclusivamente em HTML, destinado à apresentação de informações sobre o time Corinthians Monte.
2.3 Visão Geral
O documento está estruturado em seções que abordam definições, requisitos, arquitetura e possíveis evoluções do sistema.













3. GLOSSÁRIO
HTML: Linguagem de marcação utilizada para estruturar páginas web.
Página Web: Documento acessado por meio de um navegador.
Hyperlink: Elemento que permite a navegação entre páginas.
Navegador: Software responsável por interpretar HTML.
Requisito Funcional: Define o comportamento do sistema.
Requisito Não Funcional: Define restrições e qualidades do sistema.
Arquitetura: Estrutura organizacional do sistema.
MPA: Aplicação composta por múltiplas páginas independentes.
Usabilidade: Facilidade de uso do sistema.

4. DEFINIÇÃO DE REQUISITOS DO USUÁRIO
RU01: O usuário deve acessar uma página inicial com informações do clube.
RU02: O usuário deve navegar entre as páginas do site.
RU03: O usuário deve visualizar a história do clube.
RU04: O usuário deve consultar os títulos conquistados.
RU05: O usuário deve visualizar informações do elenco.


5. ARQUITETURA DO SISTEMA
5.1 Tipo de Arquitetura
O sistema utiliza arquitetura do tipo Multi-Page Application (MPA), baseada em páginas HTML interligadas.
5.2 Estrutura de Diretórios
/corinthians-monte/
│
├── index.html
├── historia.html
├── titulos.html
├── elenco.html
│
└── /assets/
        └──imagens/

5.3 Modelo de Navegação
A navegação é não linear, permitindo que todas as páginas estejam interligadas por hyperlinks, garantindo acesso completo ao conteúdo a partir de qualquer página.


6. ESPECIFICAÇÃO DE REQUISITOS DO SISTEMA
6.1 Requisitos Funcionais
RF01: O sistema deve possuir quatro páginas HTML distintas.
RF02: Todas as páginas devem possuir links entre si.
RF03: A página inicial deve conter informações gerais e menu.
RF04: A página de história deve apresentar informações do clube.
RF05: A página de títulos deve listar conquistas em ordem cronológica.
RF06: A página de elenco deve apresentar jogadores e comissão técnica.
6.2 Requisitos Não Funcionais
RNF01: O sistema deve ser desenvolvido apenas em HTML.
RNF02: O sistema deve funcionar em navegadores modernos.
RNF03: O sistema deve ser executado localmente sem servidor.
RNF04: Os arquivos devem estar organizados corretamente.
RNF05: O sistema deve apresentar navegação clara e compreensível.


7. MODELOS DE SISTEMA
Ator: Usuário
Casos de uso:

Fluxo básico:
O usuário acessa a página inicial, escolhe uma seção através do menu, navega entre páginas e visualiza as informações desejadas.


8. EVOLUÇÃO DO SISTEMA
O sistema pode ser expandido futuramente com a adição de estilos utilizando CSS, implementação de interatividade com JavaScript, integração com banco de dados e adaptação para dispositivos móveis.


9. APÊNDICES
Apêndice A: Convenções de nomeação
Os arquivos devem ser nomeados em letras minúsculas e sem espaços.
Apêndice B: Ferramentas utilizadas
Editor de código e navegador web.







