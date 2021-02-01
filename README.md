# Mestre dos Códigos - Análise de Negócios

## Prova

**Mestre dos Códigos:** Análise de Negócios

**Nível:** Cavaleiro

**Questões Técnicas:**


1. ~~Identifique os [limites do Sistema e os limites do contexto](https://www.passeidireto.com/arquivo/4611736/ireb_cpre-fl_syllabus_pt_v2-1);~~
2. ~~Elabore os [Requisitos não funcionais](https://youtu.be/Pn93e2fgIro?t=513) da aplicação;~~
3. ~~Elabore um [PVB (Product Vision Board)](https://www.youtube.com/watch?v=jKuzaIkIB68) do projeto;~~
4. ~~Crie ao menos duas [proto-personas](https://blog.caelum.com.br/entendendo-usuario-proto-persona/) principais, que se beneficiarão com a aplicação desenvolvida;~~
5. Selecione as duas funcionalidades que você julga mais complexas e elabore:
   1. ~~Protótipos de alta fidelidade;~~
   2. ~~[Diagramação de caso de uso](https://medium.com/operacionalti/uml-diagrama-de-casos-de-uso-29f4358ce4d5);~~
   3. ~~Diagramação [BPMN](https://www.lucidchart.com/pages/pt/o-que-e-bpmn#discovery__top);~~
6. ~~Com base na EAP já elaborada, sugira a ordem de priorização das funcionalidades e justifique.~~
7. ~~Com base em todas as funcionalidades levantadas elabore um [MVP](https://www.alura.com.br/artigos/voce-sabe-o-que-e-o-minimum-viable-product), descreva-o e justifique.~~

**Questões comportamentais**:

1. ~~Dado que você tenha realizado toda a análise de um projeto com característica de [escopo fechado](https://www.projectbuilder.com.br/blog/quais-os-desafios-e-as-dificuldades-de-projetos-de-escopo-fechado/) , e durante o desenvolvimento, o desenvolvedor aponta a necessidade de realizar uma alteração nos requisitos (por conta de uma regra que você tenha elicitado). Qual seria a sua conduta neste caso?~~
2. ~~Dado que você tenha realizado toda a análise de um projeto com característica de escopo fechado, e durante a etapa de desenvolvimento, o Cliente aponta a necessidade de realizar uma alteração nos requisitos. Qual seria a sua conduta neste caso?~~
3. ~~Durante o processo de elicitação, você identifica que existe um conflito de interesses entre os Stakeholders do projeto. Neste caso, o que você faria?~~



## Respostas

- **Questão 1**
  
- Limites do Sistema e Contexto: [Limite do Sistema e Contexto](./Diversos/Limite do Sistema e Contexto.png)
  
- **Questão 2**
  
- Requisitos Não Funcionais: [RN_Funcional](./Projeto - Provas/RN_Funcional.md) e [RN_InterfacePadrao](./Projeto - Provas/RN_InterfacePadrao.md)
  
- **Questão 3**
  
- Product Vision Board: [Product Vision Board](./Diversos/Product Vision Board.png)
  
- **Questão 4**
  - Proto-Persona 01: [ProtoPersona01](.\Diversos\ProtoPersona01.png)
  - Proto-Persona 02: [ProtoPersona02](.\Diversos\ProtoPersona02.png)

- **Questão 5**
  - Protótipos de Alta fidelidade: https://www.figma.com/file/fUrKAFfFkgCDLMwKzg3dId/API-Provas-Copy?node-id=0%3A1
  - Diagrama de Caso de Uso: [Diagrama de Caso de Uso UML](./Diversos/Diagrama de Caso de Uso UML.png)
  - Diagrama BPMN: [Fluxograma](./Diversos/Fluxograma.png)

- **Questão 6**

  - **Justificativa da EAP:** Conforme disposto na [EAP](./Diversos/EAP - Provas.png), iniciaremos o desenvolvimento focado em gerar valor possibilitando o usuário de criar e manipular provas e questões de alguns tipos, também teremos a disponibilização da página Home contendo os acesso principais a funcionalidades do sistema. O acesso a ferramenta será habilitado porém sem a separação dos tipos de usuários.

    Para segunda entrega iremos gerar valor criando o permissionamento dos usuários para que possamos também desenvolver na terceira entrega a manipulação e gerenciamento dos resultados das provas contidas na ferramenta. Junto desta entrega iremos disponibilizar mais três tipos de questões, garantindo versatilidade da geração de provas para diversas áreas educacional/profissional.

    Por fim iremos entregar a área de automação de provas, visando criar uma forma de integração entre sistemas para o envio e correção de provas padrão.

- **Questão 7:**

  - **MVP01**
    - Acesso a aplicação web sem diferenciação de usuários;
    - Criar provas utilizando questões preexistentes;
    - Visualizar questões preexistentes para serem adicionadas nas provas;
  - **Justificativa:** Serão desenvolvidos os acesso básicos a aplicação possibilitando a navegação e testagem da funcionalidade principal de geração das provas, esta ação será executada utilizando questões preexistentes em banco visando a validação da metodologia de criação das provas. Desta forma os *stakeholders* conseguirão notar o valor agregado a ferramenta em questão.
  - **Matriz de Decisões:**

![](.\Diversos\Matriz MVP.png)



**Questões comportamentais**:

1. Dado que você tenha realizado toda a análise de um projeto com característica de [escopo fechado](https://www.projectbuilder.com.br/blog/quais-os-desafios-e-as-dificuldades-de-projetos-de-escopo-fechado/) , e durante o desenvolvimento, o desenvolvedor aponta a necessidade de realizar uma alteração nos requisitos (por conta de uma regra que você tenha elicitado). Qual seria a sua conduta neste caso?

**Resposta:** Neste caso eu iria analisar o cenário exposto pelo Desenvolvedor, validar todo o contexto e discutir com os stakeholders sobre uma possível alteração nos requisitos devido a regra de negócios não mapeada anteriormente, lembrando que a gestão sempre deverá negociar com o cliente sobre o ocorrido e mostrar os pontos bons e ruins desta alteração.



2. Dado que você tenha realizado toda a análise de um projeto com característica de escopo fechado, e durante a etapa de desenvolvimento, o Cliente aponta a necessidade de realizar uma alteração nos requisitos. Qual seria a sua conduta neste caso?

**Resposta:** Neste caso eu iria analisar o cenário exposto pelo Cliente, validar se esta funcionalidade ou regra já foi contemplada de alguma forma, expor os riscos e benefícios desta alteração e solicitar o alinhamento entre a gestão do projeto para alterações de contrato.



3. Durante o processo de elicitação, você identifica que existe um conflito de interesses entre os Stakeholders do projeto. Neste caso, o que você faria?

**Resposta:** Dado que em meio ao processo de elicitação ocorra conflitos de interesses entre os envolvidos, eu como analista de negócios irei intermediar todo o cenário para que possamos avaliar todas as opiniões, validar as informações abordadas, procurar a melhor alternativa e propor uma solução que tenha menos impacto e maior aderência entre as partes, pois nunca seremos perfeitos, mas podemos negociar sempre.