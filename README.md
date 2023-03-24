# Desenvolvimento de Sistemas <img src="assets/7069799.png" width="10%" height="10%" align="right" valign="center"/> 

![learning](https://img.shields.io/badge/PHP-learning-green.svg)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/vitoriape/php-handbook&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Views&edge_flat=false)](https://hits.seeyoufarm.com)
<!--ts-->
* [Sistemas de Softwares](#sistemas-de-softwares)
  * [Características Gerais](#características-gerais)
  * [Características Técnicas](#características-técnicas)
* [Paradigmas de Desenvolvimento](#paradigmas-de-desenvolvimento)
  * [Paradigma Estruturado](#paradigma-estruturado)
  * [Paradigma Orientado a Objetos](#paradigma-orientado-a-objetos)
* [Etapas de Desenvolvimento](#etapas-de-desenvolvimento)
  * [Análise](#análise)
  * [Projeto](#projeto)
  * [Construção](#construção)
  * [Testes](#testes)
  * [Implantção](#implantação)
  * [Manutenção](#manutenção)
* [Viabilidade Financeira](#viabilidade-financeira)
* [Viabilidade Técnica](#viabilidade-técnica)
* [Dimensionamento do Projeto](#dimensionamento-do-projeto)
* [Gestão da Qualidade-Riscos-Pessoas](#gestão-da-qualidade-riscos-pessoas)
* [Requisitos de Qualidade do Software](#requisitos-de-qualidade-do-software)
  * [Requisitos Não Funcionais](#requisitos-não-funcionais)
<!--te-->

---
---

## **Sistemas de Softwares**
### **Características Gerais**
#### **Invisibilidade**
Softwares não são visíveis ou tangíveis, somente os resultados do seu trabalho.

#### **Complexidade**
Os elementos interagem de forma não linear e a ampliação de um software não depende da repetição desses elementos, mas sim ampliar sua funcionalidade.

#### **Mutabilidade**
Os sistemas de softwares estão em constante mudança.

#### **Conformidade**
Quando o cliente começa a utilizar o software, gerando resultados, é obrigatório que o mesmo esteja em conformidade com seu escopo e objetivo.

#### **Inalterabilidade**
Softwares não se desgastam fisicamente.

---

### **Características Técnicas**
#### **Reusabilidade**
Os componentes de um software podem ser reaproveitados por outro.

#### **Manutenibilidade**
Um sistema de software precisa evoluir para atender novas necessidades do cliente final.

#### **Confiança e Proteção**
Garantia de que o software não falhará e manterá seus dados sensíveis seguros.

#### **Eficiência**
Não se deve desperdiçar recursos do sistema, tal como memória e processamento.

#### **Aceitabilidade**
O software deve ser aceitável para o usuário, cumprindo um certo nível de usabilidade dentro daquilo que foi requisitado.

---
---

## **Paradigmas de Desenvolvimento**
Norma ou conjunto de diretrizes do desenvolvimento de projetos de softwares.

### **Paradigma Estruturado**
Focado nas operações intermediadas pelo software e nas transformações de dados. Acabou tornando-se obsoleto para as aplicações atuais.

#### **Projeto Estruturado**
O processo de desenvolvimento transita entre cada etapa uma única vez, causando lentidão e mais trabalho.

---

### **Paradigma Orientado a Objetos**
Um objeto é um artefato de software (não tangível e abstraído, "simulado") que incorpora atributos e as operações que envolvem os mesmos. 

<table><thead><tr><th colspan="2">Principais Características</th></tr></thead><tbody><tr><td>Independência</td><td>Os objetos, seus atributos e operações são unidades independentes</td></tr><tr><td>Armazenamento</td><td> O detalhamento do armazenamento dos atributos não é de conhecimento externo, ou seja, os requisitos de funcionamento do software devem estar dentro do mesmo</td></tr><tr><td>Reutilização</td><td>Já na criação do escopo do projeto deve-se pensa em reuso de componentes</td></tr><tr><td>Manutenção</td><td>O foco é desenvolver mais facilmente e mais rapidamente</td></tr><tr><td>Programação Estruturada</td><td>Ao aumentar a complexidade de um sistema, o ideal é produzir unidades menores e independentes ao invés de grandes blocos operacionais complexos</td></tr></tbody></table>

#### **Projeto Orientado a Objetos**
O processo de desenvolvimento passa diversas vezes por cada etapa e, esse conjunto de etapas, é o que desenvolve o objeto.

---
---

## **Etapas de Desenvolvimento**
Análise - Projeto - Construção - Testes - Implantação - Manutenção

### **Análise**
`[O quê?]`
Nela, é estabelecida a maneira mais viável de solucionar um problema. São identificadas as necessidades funcionais e os requisitos técnicos.

<table><thead><tr><th colspan="2">Etapas</th></tr></thead><tbody><tr><td>Identificação</td><td>São indicas as necessidades do sistema</td></tr><tr><td>Avaliação</td><td>Detalhamento da concepção do sistema quanto à sua realização</td></tr><tr><td>Realização</td><td>Análise da viabilidade econômica e viabilidade técnica</td></tr><tr><td>Atribuição</td><td>Incumbência das funções de cada elemento do sistema, hardware, software, pessoas, banco de dados e afins</td></tr><tr><td>Estabelecimento</td><td>Apontamento das restrições de prazo e de custo operacional</td></tr></tbody></table>

---

### **Projeto**
`[Como?]`
Viabiliza tecnicamente as atribuições do sistema.

<table><thead><tr><th colspan="2">Escopo</th></tr></thead><tbody><tr><td>Estrutura de Dados</td><td>Representa um relacionamento lógico entre elementos e dados</td></tr><tr><td>Procedimentos</td><td>Hierarquia de controle ligada ao processamento, ou seja, detalhamento das operações</td></tr><tr><td>Arquitetura de Software</td><td>Organização dos componentes de um programa considerando a estrutura de dados</td></tr><tr><td>Interfaces</td><td>Fluxo de informações levando em conta a interação do usuário, com outros sistemas e com os componentes internos</td></tr></tbody></table>

---

### **Construção**
`[Programação]`
Modularidade do software segmentando o mesmo em componentes posteriormente integrados para atender aos requisitos estabelecidos.

- Considera a criação de um banco de dados e seu controle, realizado pelo sistema de gerenciamento de BD.

#### **Integração**
`[Backlink]` A Integração Incremental elimina a necessidade de prontidão para uso de todos os componentes, otimizando também a realização de testes e localização de erros.

<table><thead><tr><th colspan="2">Integração</th></tr></thead><tbody><tr><td colspan="2">Pode considerar a integralização de componentes do mesmo sistema ou entre sistemas distintos.</td></tr><tr><td>Integração Simultânea</td><td>Todos os componentes são agrupados de uma vez só</td></tr><tr><td>Integração Incremental</td><td>Os componentes vão sendo integrados um de cada vez</td></tr></tbody></table>

---

### **Testes**
`[Prévia]` Visa garantir que todas as instruções foram testadas, buscando defeitos de função, lógica e implantação.

<table><thead><tr><th colspan="3">Tipificação de Testes</th></tr></thead><tbody><tr><td>Tipo</td><td>Descrição</td><td>Exemplo</td></tr><tr><td>Testes de Unidade</td><td>Analisam o funcionamento de um componente de software</td><td>Função, procedimento, método ou módulo</td></tr><tr><td>Testes de Integração</td><td>Verificam se os componentes operam em grupo</td><td>Interface entre os componentes</td></tr><tr><td>Testes de Validação</td><td>Avalia se o software está de acordo com a solicitação do cliente após a integração</td><td>Testes Alfa (desenvolvimento) e Beta (usuário)</td></tr></tbody></table>

>---

Antes do Teste do Validação, é possivel realizar alguns testes com o software pronto:

<table><thead><tr><th colspan="2">Testes de Sistema</th></tr></thead><tbody><tr><td>Recuperação</td><td>Forçar uma falha e verificar como o sistema se recupera</td></tr><tr><td>Segurança</td><td>Evita invasões e previne a perda de dados</td></tr><tr><td>Esforço</td><td>Como o sistema se mantém disponível sob demandas fora do previsto</td></tr><tr><td>Desempenho</td><td>Funcionamento do software de acordo com o especificado e esperado</td></tr><tr><td>Usabilidade</td><td>Interface, navegação e facilidade de uso pelo usuário</td></tr><tr><td>Portabilidade</td><td>Como o sistema opera em ambientes distintos</td></tr></tbody></table>

---

### **Implantação**
`[Disponibilidade]` O software é finalmente instalado e fica disponível para os clientes/usuários. Para tal, são realizadas as conexões com outros sistemas e importações/migrações de dados.

<table><thead><tr><th colspan="2">Implantação de Sistemas</th></tr></thead><tbody><tr><td>Lançamento</td><td>O software sofre empacotamento, ou seja, são disponibilizados os pacotes necessários. Pode incorrer também o anúncio do mesmo.</td></tr><tr><td>Instalação</td><td>Transferência do software do desenvolvedor para o cliente, configuração e ativação. O sistema é parametrizado de acordo com as necessidades paralelas.</td></tr></tbody></table>

---

### **Manutenção**
`[Modificação]` Primeiro, um processo é implementado. Em seguida, faz-se a análise do problema e da alteração necessária. A alteração é então implementada, revisada e aceita. Por fim, é realizada a migração.

<table><thead><tr><th colspan="2">Manutenção de Sistemas</th></tr></thead><tbody><tr><td>Manutenção Corretiva</td><td>Corrige falhas de processamento</td></tr><tr><td>Manutenção Adaptativa</td><td>Torna o software mais apto para mudanças no ambiente de processamento</td></tr><tr><td>Manutenção Perfectiva</td><td>Inclui novas funcionalidades</td></tr><tr><td>Manutenção Preventiva</td><td>Melhora a confiabilidade do sistema</td></tr></tbody></table>

---

## **Viabilidade Financeira**
Relação entre custos e benefícios na qual os custos não devem sobrepor os benefícios.

<table><thead><tr><th>Custos</th><th>Benefícios</th></tr></thead><tbody><tr><td>Recursos Humanos</td><td>Inovação</td></tr><tr><td>Hardware</td><td>Flexibilidade</td></tr><tr><td>Materiais de Consumo</td><td>Qualidade</td></tr><tr><td>Software</td><td>Produtividade</td></tr><tr><td>Operação e Manutenção</td><td>Custo</td></tr></tbody></table>

---

## **Viabilidade Técnica**
<table><thead><tr><th>Checkup</th><th>Descrição</th></tr></thead><tbody><tr><td>Transferência de Informações</td><td>Verificação da viabilidade de input e output de dados entre sistemas</td></tr><tr><td>Requerimento de Tecnologia</td><td>Checagem da possibilidade de demanda do software por novas tecnologias</td></tr><tr><td>Disponibilidade de Recursos</td><td>Disponibilidade de recursos técnicos para a aplicação</td></tr><tr><td>Conhecimento Técnico</td><td>Validação de conhecimento técnico por parte da organização para o desenvolvimento</td></tr></tbody></table>

---

## **Dimensionamento do Projeto**
Relação entre recursos em função de um tempo pré determinado.
<table><thead><tr><th>Recursos</th><th>Exemplo</th></tr></thead><tbody><tr><td>Humanos</td><td>Equipe e know-how</td></tr><tr><td>Ambientais</td><td>Hardware, ferramentas e rede</td></tr><tr><td>Reutilização de Software</td><td>Componentes de software</td></tr></tbody></table>

>---

<table><thead><tr><th>Tempo</th><th>Definição</th></tr></thead><tbody><tr><td>Escopo</td><td>Definição e sequenciamento das atividades</td></tr><tr><td>Recurso</td><td>Atribuição dos recursos demandados para cada atividade</td></tr><tr><td>Cronograma</td><td>Estima da duração das atividades e elaboração do cronograma</td></tr></tbody></table>

---

## **Gestão da Qualidade-Riscos-Pessoas**
Reconhece a importância da satisfação do cliente, privilegiando a prevenção, a melhoria contínua, a responsabilidade da gerência e os custos da qualidade.
<table><thead><tr><th colspan="2">Gerenciando Qualidade</th></tr></thead><tbody><tr><td>Garantia de Qualidade</td><td>Visa estabelecer uma estrutura padronizada de procedimentos</td></tr><tr><td>Planejamento da Qualidade</td><td>Seleção de padrões apropriados para as demandas do projeto</td></tr><tr><td>Controle da Qualidade</td><td>Assegura que a equipe valeu-se dos procedimentos e padrões de qualidade</td></tr></tbody></table>

>---

<table><thead><tr><th colspan="2">Gerenciando Riscos</th></tr></thead><tbody><tr><td>Tipos de Riscos</td><td>Podem ser relacionados ao projeto em si, ao produto ou ao empreendimento</td></tr><tr><td>Riscos Negativos</td><td>Eliminam, transferem, mitigam ou aceitam</td></tr><tr><td>Riscos Positivos</td><td>Exploram, compartilham, melhoram ou aceitam</td></tr></tbody></table>

>---

<table><thead><tr><th colspan="2">Gerenciando Pessoas</th></tr></thead><tbody><tr><td>Plano de RH</td><td>Atribui os papéis, as responsabilidades, as habilidades necessárias, a hierarquia envolvida e o plano de gerência</td></tr><tr><td>Mobilização</td><td>Estabelece a movimentação da equipe do projeto</td></tr><tr><td>Desenvolvimento</td><td>Visa melhorar as competências, a comunicação e o ambiente de trabalho da equipe</td></tr><tr><td>Gerenciamento</td><td>Gerência executiva da equipe e de suas atribuições</td></tr></tbody></table>

>---

<table><thead><tr><th colspan="2">Gerenciando Configurações</th></tr></thead><tbody><tr><td>Item de Configuração</td><td>Qualquer item gerado no desenvolvimento, como módulos, que seja candidato para sofrer um controle de modificações</td></tr><tr><td rowspan="5">Plano de Gerenciamento</td><td>Define os itens a serem gerenciados</td></tr><tr><td>Estabelece as responsabilidades</td></tr><tr><td>Cria políticas de gerenciamento</td></tr><tr><td>Especifica as ferramentas de controle</td></tr><tr><td>Descreve a estrutura de registro das informações</td></tr></tbody></table>

---
---

## **Requisitos de Qualidade do Software**
### **Requisitos Não Funcionais**
Conhecidos também como requisitos de qualidade do software, e se relacionam com a natureza do mesmo que independe do seu funcionamento.

- **Manutenibilidade**
Grau de facilidade de modificação ao longo da evolução do software.

- **Confiança e Proteção**
Segurança do programa.

- **Eficiência**
Relaciona-se com o uso de banda, rede, RAM e afins.

- **Aceitabilidade**
Nível de nivelamento da natureza do software em relação ao que o cliente solicitou.

---
---
