
# ✅ Lista de Verificação de Controles e Conformidade – Botium Toys

## 🔒 Controles Administrativos

| Controle                          | Aplicado? | Observações / Recomendações                                                                 |
|----------------------------------|-----------|---------------------------------------------------------------------------------------------|
| Política de senhas               | ❌        | Política atual é fraca. Reforçar complexidade mínima e implementar sistema de gerenciamento. |
| Privilégio mínimo (Least Privilege) | ❌        | Todos os funcionários têm acesso a dados sensíveis. Implementar controles baseados em função. |
| Separação de funções             | ❌        | Não foi implementada. Reduzir riscos internos e falhas operacionais.                        |
| Plano de recuperação de desastres | ❌        | Não existe. Criar e testar plano com backups regulares.                                     |
| Política de controle de acesso   | ❌        | Ainda não definida. Criar e aplicar imediatamente.                                          |

## 💻 Controles Técnicos

| Controle                   | Aplicado? | Observações / Recomendações                                                             |
|---------------------------|-----------|-----------------------------------------------------------------------------------------|
| Firewall                  | ✅        | Já implementado com regras apropriadas.                                                |
| IDS/IPS                   | ❌        | Não implementado. Recomendado para detecção precoce de invasões.                       |
| Criptografia              | ❌        | Informações de cartão e PII não são criptografadas. Urgente implementar.               |
| Antivírus                 | ✅        | Instalado e monitorado regularmente.                                                   |
| Backup de dados           | ❌        | Nenhum backup implementado. Risco crítico.                                             |
| Gerenciamento de senhas   | ❌        | Não centralizado. Afeta produtividade e segurança.                                     |
| Monitoramento de sistemas legados | ❌        | Monitoramento existe, mas sem cronograma ou processo definido.                         |

## 🏢 Controles Físicos

| Controle                           | Aplicado? | Observações / Recomendações                                                       |
|-----------------------------------|-----------|-----------------------------------------------------------------------------------|
| Câmeras de vigilância (CCTV)      | ✅        | Presente e funcionando.                                                          |
| Trancas e fechaduras              | ✅        | Presentes e adequadas para o escritório, loja e depósito.                         |
| Sistema de prevenção de incêndios | ✅        | Presente e funcional.                                                            |

## 📋 Checklist de Conformidade

| Regulamento                      | Aplicado? | Observações / Recomendações                                                                 |
|----------------------------------|-----------|---------------------------------------------------------------------------------------------|
| **GDPR**                         | ✅        | Existe plano de notificação em 72h e políticas internas de privacidade.                    |
| **PCI DSS**                      | ❌        | Não há criptografia para transações com cartão nem controle de acesso adequado.            |

## 📝 Recomendações Gerais para a Gerente de TI

1. **Priorizar a implementação de criptografia** para dados de pagamento e PII.
2. **Criar um plano de recuperação de desastres** e implementar **backups regulares**.
3. Estabelecer políticas formais de **acesso com privilégio mínimo** e **separação de funções**.
4. Instalar e configurar um sistema de **detecção de intrusões (IDS)**.
5. **Atualizar e aplicar a política de senhas**, com gerenciamento centralizado.
6. Desenvolver plano de **conformidade com o PCI DSS** para operações com cartão de crédito.
