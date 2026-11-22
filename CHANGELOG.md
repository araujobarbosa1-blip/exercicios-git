# Histórico de Alterações (Changelog)

Todas as alterações notáveis neste projeto serão documentadas neste arquivo.

## [2.0.0] - 2026-09-20
### Alterações Incompatíveis (Breaking Changes - MAJOR)
- **Remoção de Função Pública:** Removido o método legado de autenticação `loginViaSessao()`, substituído por tokens JWT.
- **Banco de Dados:** Reformulado o esquema da tabela `usuarios`, exigindo execução de migração prévia.

### Adicionado
- Suporte nativo à autenticação de dois fatores (2FA).

## [1.1.0] - 2026-08-15
### Adicionado (MINOR)
- **Exportação de Dados:** Implementada a funcionalidade de exportação de dados em formatos CSV e PDF.
- **Busca:** Adicionada barra de pesquisa dinâmica com filtros avançados por data e categoria.

### Alterado
- Otimizada a velocidade de carregamento da listagem principal de registros.

## [1.0.1] - 2026-07-01
### Corrigido (PATCH)
- **Interface:** Corrigida falha de renderização no menu lateral responsivo em telas menores.
- **Desempenho:** Corrigido vazamento de memória ao fechar conexões assíncronas do banco.
