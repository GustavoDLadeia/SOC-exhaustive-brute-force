# Brute Force Exaustivo

## Cenário

Investigação envolvendo múltiplas tentativas de autenticação seguidas de sucesso, indicando possível ataque de brute force e risco de comprometimento de conta.

---

## Resumo

Múltiplas tentativas falhas de login em curto período de tempo foram detectadas para o usuário `joao.silva` a partir de um IP externo (`103.45.78.22`), originado de uma localização incomum para o sistema (**Rússia**), seguidas de uma tentativa de login bem-sucedida em horário atípico (`03:12 AM`).

---

## Evidências

| Campo | Valor |
|---|---|
| Usuário | `joao.silva` |
| IP de origem | `103.45.78.22` |
| Localização | Rússia |
| Tentativas falhadas | 20 em 3 minutos |
| Intervalo entre tentativas | Poucos segundos |
| Login bem-sucedido após as falhas | Sim |
| Horário do login | 03:12 AM |

---

## Análise

- O volume elevado de tentativas de login em curto período é consistente com comportamento de **brute force**.
- A origem geográfica incomum e o horário atípico reforçam a suspeita de atividade maliciosa.
- O sucesso no login após múltiplas falhas aumenta significativamente o risco de comprometimento da conta.

---

## Conclusão

Atividade suspeita compatível com ataque de brute force com possível comprometimento de conta.

---

## Ações Recomendadas

- Resetar a senha do usuário
- Verificar atividades realizadas após o login
- Bloquear temporariamente o IP de origem
- Recomendar uso de autenticação multifator (**MFA**)
