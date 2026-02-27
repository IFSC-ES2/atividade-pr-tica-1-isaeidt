Governança do Repositório
Regras básicas

Proibição de Push: Proibido commit direto na main (tudo entra por PR).


Padronização de Branches: 


feature/<id>-<resumo> 


fix/<id>-<resumo> 


chore/<id>-<resumo> 

Mensagens de Commit: Devem ser claras e, preferencialmente, utilizar o padrão Conventional Commits (ex: feat:, fix:, docs:).

DoD do PR (mínimo)

Descrição: Detalhar o que mudou, por quê e como testar.


Auto-review: Checklist preenchido e comentários técnicos realizados no próprio PR.

Qualidade de Código: O código deve estar livre de trechos comentados desnecessários e seguir as regras de linting do projeto (se houver).

Evidências: Inclusão de prints ou logs que comprovem que a alteração funciona conforme o esperado.

Review (critérios)

Comunicação: Comentários devem explicar o motivo técnico e sugerir alternativa quando possível, mantendo um tom colaborativo.


Atomicidade: Evitar PR grande: se não revisa em ~10 min, dividir em partes menores.


Resolução de Conversas: Todas as discussões iniciadas no PR devem ser marcadas como "Resolved" antes do merge.

Foco em Lógica: Priorizar a análise da lógica de negócio e segurança sobre preferências puramente estéticas.
