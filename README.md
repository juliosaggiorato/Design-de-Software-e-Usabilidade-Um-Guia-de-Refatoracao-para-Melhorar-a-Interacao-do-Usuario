# Checklist de Refatoração de Usabilidade

Este checklist é parte integrante do Trabalho de Conclusão de Curso 'Design de Software e Usabilidade: Um Guia de Refatoração para Melhorar a Interação do Usuário', apresentado ao curso de Engenharia de Software da Universidade Tecnológica Federal do Paraná. Ele compila boas práticas extraídas de 10 estudos sobre refatoração e usabilidade, o mesmo assegura a aplicação das boas práticas identificadas na literatura como um ciclo continuo de melhoria.

## 1. Planejamento Estratégico e Diagnóstico (PE)
*Fase de preparação e identificação de problemas.*

- [ ] **Identificação de Smells:** Identifiquei "usability smells" (ex: links enganosos, validação tardia) que indicam problemas de design?
- [ ] **Avaliação Heurística:** Realizei uma inspeção baseada em princípios (ex: Nielsen) para encontrar falhas óbvias?
- [ ] **Teste com Usuários:** Observei usuários reais utilizando o sistema para capturar dificuldades de uso?
- [ ] **Métricas de Base:** Defini métricas quantitativas atuais (ex: pontuação SUS, tempo de tarefa) para comparação futura?
- [ ] **Mapeamento de Processo:** Mapeei o fluxo atual (AS IS) para entender onde o processo falha?
- [ ] **Personas:** Criei proto-personas para alinhar a refatoração às necessidades do público-alvo?
- [ ] **Cenários:** Documentei os cenários de uso e tarefas críticas que serão testados?

## 2. Refatoração Orientada à Experiência (RUX)
*Fase de design e definição da solução.*

- [ ] **Mapeamento Problema-Solução:** Para cada *smell* identificado, defini uma refatoração específica correspondente?
- [ ] **Aplicação de Heurísticas:** O novo design respeita as 10 Heurísticas de Nielsen (ex: visibilidade do status)?
- [ ] **Regras de Interação:** As 8 Regras de Shneiderman (ex: feedback informativo, consistência) foram aplicadas?
- [ ] **Leis Cognitivas:** A organização visual respeita leis como Gestalt, Fitts e Hick?
- [ ] **Padrões de Interface:** Utilizei padrões (UI Patterns) conhecidos (ex: Wizard, Breadcrumbs) em vez de reinventar componentes?
- [ ] **Acessibilidade:** A solução proposta atende aos critérios básicos de acessibilidade?
- [ ] **Prototipação:** Criei wireframes ou protótipos para validar a solução visualmente antes de codificar?
- [ ] **Validação A/B:** Planejei um Teste A/B para comparar a versão original com a refatorada?

## 3. Execução Técnica (ETR) e Resultados
*Fase de implementação e verificação.*

- [ ] **Refatoração Client-Side:** (Se aplicável) Utilizei CSWRs para implementar a mudança no front-end de forma ágil para testes?
- [ ] **Refatoração de Modelos:** As mudanças foram estruturadas nos modelos de navegação e apresentação, não apenas cosméticas?
- [ ] **Migração Gradual:** (Para legados) Adotei uma estratégia de convivência entre o sistema novo e o antigo para evitar riscos?
- [ ] **Implementação Definitiva:** A solução validada foi implementada permanentemente no código do servidor (back-end)?
- [ ] **Documentação:** As decisões técnicas e de design foram documentadas para manutenção futura?
- [ ] **Verificação de Impacto:** As métricas coletadas após a refatoração mostram melhoria em relação à linha de base?
