# Política de integridade e versionamento

A monografia original na raiz do TCC é imutável. Versão-base: BASE-2026-10-26-090607; SHA-256: 3A18FB63A78380D7BAACDA70FA6AC2A02E1755A2B68B8E90D08ED56B06DB6ECC. O hash identifica bytes, não comprova aprovação do professor. Planilhas originais, dados brutos, mídias, orientações e diagnósticos anteriores também são preservados.

## Antes e depois
Confirmar caminho e hash de toda origem relevante, registrar data, agente e ID. Se o hash divergir, suspender a operação dependente da versão e relatar a divergência. Produzir propostas em arquivo isolado. Edições autorizadas devem ocorrer em cópia versionada; conferir efeito e hash final. Nenhum agente sobrescreve o DOCX-base ou um XLSX original.

## Compatibilidade
O procedimento existente em Saídas e Registros/Controle de Versões/README.md e registro_de_alteracoes.csv continua válido. O novo controle complementa esse registro, sem alterar cabeçalho ou estados. Para integração aprovada: comparar o hash atual da origem com o hash registrado na proposta; se divergir, manter pendente e reavaliar o trecho. Integrar somente em arquivo novo em Saídas e Registros/Versões, registrar destino e SHA-256. O Agente 08 não altera o original.

## Duas camadas de estado
Nesta arquitetura, PROPOSTO significa alteração sugerida; HOMOLOGADO TECNICAMENTE significa entrega conferida; APROVADO PELO PROPRIETÁRIO exige decisão humana expressa; INTEGRADO EM VERSÃO CONTROLADA exige arquivo novo e hash. Para alterações da monografia, usar também os estados do CSV antigo: PROPOSTA, PENDENTE, APROVADA, REJEITADA e INTEGRADA. Homologação técnica não deve ser inscrita como APROVADA. O modelo de registro aponta para o esquema antigo sem substituí-lo.
