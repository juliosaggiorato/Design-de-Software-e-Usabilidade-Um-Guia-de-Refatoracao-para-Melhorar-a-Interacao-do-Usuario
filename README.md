# Checklist de Refatoração para melhoria de usabilidade do usuário

Este checklist é parte integrante do Trabalho de Conclusão de Curso 'Design de Software e Usabilidade: Um Guia de Refatoração para Melhorar a Interação do Usuário', apresentado ao curso de Engenharia de Software da Universidade Tecnológica Federal do Paraná. Ele compila boas práticas extraídas de 10 estudos sobre refatoração e usabilidade, o mesmo assegura a aplicação das boas práticas identificadas na literatura como um ciclo continuo de melhoria.

## 1. Planejamento Estratégico e Diagnóstico (PE)
*Fase de preparação e identificação de problemas.*

- [ ] **Identificação de Smells:** Foram identificados todos "usability smells" relevantes que indicam problemas de design?
- [ ] **Teste com Usuários:** Foram realizados testes de usabilidade com usuários reais?
- [ ] **Avaliação Heurística:** A interface passou por avaliação heurística?
- [ ] **Métricas de Base:** Métricas quantitativas foram definidas como linha de base (ex: pontuação SUS, tempo de tarefa) para comparação futura?
- [ ] **Metodologia centrada no usuário:** Foi definida metodologia que orienta refatoração as necessidades do usuário?
- [ ] **Mapeamento de Processo:** O fluxo atual (AS IS) foi mapeado para entender onde o processo falha?
- [ ] **Personas:** Foram criadas proto-personas para alinhar a refatoração às necessidades do público-alvo?
- [ ] **Cenários:** Foram documentados os cenários de uso e tarefas críticas que serão testados?

## 2. Refatoração Orientada à Experiência (RUX)
*Fase de design e definição da solução.*

- [ ] **Mapeamento Problema-Solução:** Cada smell foi relacionado a um tipo de refatoração?
- [ ] **Processo Iterativo (Ciclo de Melhoria)**: Foi adotado processo iterativo de melhoria contínua?
- [ ] **Validação A/B:** Testes A/B foram aplicados para validação objetiva?
- [ ] **Aplicação de Heurísticas:** As heurísticas de Nielsen foram aplicadas ao redesign?
- [ ] **Regras de Interação:** As regras de Shneiderman foram consideradas?
- [ ] **Leis da Psicologia e UX:** A organização visual respeita leis como Gestalt, Fitts e Hick (leis cognitivas)?
- [ ] **Padrões de Design de interface:** Padrões de interface (UI Patterns) foram incorporados?
- [ ] **Princípios Gestalt:** Foram considerados principios Gestalt (proximidade, similaridade e continuidade)?
- [ ] **Acessibilidade:** A solução proposta atende aos critérios básicos de acessibilidade?
- [ ] **Prototipação:** Criei wireframes ou protótipos para validar a solução visualmente antes de codificar?

## 3. Execução Técnica (ETR) e Resultados
*Fase de implementação e verificação.*

- [ ] **Refatoração Client-Side:** Foram aplicadas refatorações do lado do cliente (CSWRs), quando aplicável?
- [ ] **Refatoração de Modelos:** Refatorações baseadas em modelos (navegação / apresentação) foram utilizadas?
- [ ] **Migração Gradual:** Estratégias de migração gradual foram adotadas em sistemas legados?
- [ ] **Implementação melhor versão:** A melhor versão foi implementada de forma permanente?
