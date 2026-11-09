# Política de execução e delegação

A implantação de uma ficha ou prompt não ativa um chat nem um subagente. Estados separados: CONFIGURADO — DISPONÍVEL SOB DEMANDA; CHAT INDIVIDUAL ATIVO após abertura real; SUBAGENTE EM EXECUÇÃO após delegação verificável. Os estados de Controle/ESTADO_DOS_AGENTES.csv são de configuração e histórico; não provam conversa ativa.

## Fluxo de tarefa
1. Receber prompt expresso do proprietário e confrontar autorização, versão, dados permitidos, escrita e critérios.
2. Registrar a ordem e confirmar arquivos reais. Consultar skills aplicáveis.
3. Se houver delegação expressa, o MAESTRO inicia apenas o especialista indicado e registra identificador real. Nenhuma cadeia automática de especialistas.
4. O executor produz propostas/relatório em saída isolada, com evidências e limites; não edita arquivos de outro agente nem originais.
5. O MAESTRO verifica o conteúdo, hashes, escopo e artefatos e registra homologação técnica ou pendência.
6. Encerrar a tarefa. Uma recomendação futura requer novo prompt do proprietário.

Revisões independentes podem coexistir em arquivos próprios, mas ninguém escreve concorrentemente no DOCX principal. Um erro de autorização, hash ou acesso bloqueia somente as operações afetadas e deve aparecer no relatório. Não declarar execução efetiva por existir uma descrição de agente.
