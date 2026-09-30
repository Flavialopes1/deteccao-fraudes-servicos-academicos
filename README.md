# Sistema de Deteção de Fraudes nas Notas - Serviços Académicos

## 1. Processo de Engenharia de Software II (Modelo em Espiral)

### A. Obtenção de Requisitos
- **Resultado:** Requisitos funcionais e não funcionais.
- **RF01:** Deteção de alterações manuais de notas fora do período de avaliação oficial.
- **RF02:** Envio de alertas em tempo real à comissão de ética ao detetar padrões suspeitos.
- **RNF01:** Registo de auditoria imutável (logs de acessos e alterações com timestamp).
- **RNF02:** Conformidade total com as normas de proteção de dados (RGPD).

### B. Análise e Negociação de Requisitos
- **Resultado:** Requisitos negociados.
- **Ajuste:** Definição da sensibilidade dos alertas para evitar falsos positivos em correções legítimas de pautas efetuadas pelos docentes.

### C. Documentação de Requisitos
- **Resultado:** Requisitos descritos.
- Mapeamento detalhado das regras de auditoria, perfis de acesso autorizados e fluxos de alteração de dados.

### D. Validação de Requisitos
- **Resultado:** Relatório de validação.
- Simulação de cenários de fraude e validação do fluxo do sistema com os responsáveis pelo serviço académico.

---

## 2. Requisitos Voláteis
1. **Regras e Padrões de Deteção de Fraude:** Os métodos de fraude alteram-se continuamente, exigindo atualização constante das regras de deteção.
2. **Legislação e Regulamentos Académicos:** Mudanças no regulamento interno de avaliação ou em leis de proteção de dados.
3. **Integração com Novos Sistemas:** Atualizações e trocas de plataformas e-learning e bases de dados da instituição.
