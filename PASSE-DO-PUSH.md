# PASSE DO PUSH — org latesconcept · tag v1.0-lancamento

Fonte única desta pasta: `GITHUB-LATES-CONCEPT-V1.0-FINAL`. Substitua qualquer build anterior por ela. Os 5 diretórios viram 5 repositórios:

| Pasta nesta origem | Repositório na org |
|---|---|
| (arquivos raiz) | `latesconcept` (página da org) |
| `01-tratado-ponto-zero` | `01-tratado-ponto-zero` |
| `02-caderno-de-formulas` | `02-caderno-de-formulas` |
| `03-projeto-aurora` | `03-projeto-aurora` |
| `04-bancada-prototipos` | `04-bancada-prototipos` |

Passos:
1. Org: o autor cria `latesconcept` em github.com (grátis, plano Free, pública) — 2 min, só ele pode criar (login no site). Fallback: repositórios públicos na conta pessoal + transferência depois (histórico preservado).
2. Criar os 5 repositórios (sem README próprio — a origem já traz).
3. Push de cada pasta (git init no diretório, add ., commit "v1.0: estado canônico congelado", push main).
4. Verificar que os SHAs dos arquivos públicos batem com `MANIFESTO_SHA256_V1.0.csv` (rodar o mesmo script de sondagem nos dois lados).
5. **24/11/2026 00h01 BRT**: tag `v1.0-lancamento` nos 5 repositórios (mensagem: "Estado canônico no lançamento dos quatro livros — 24/11/2026 00h01 BRT") e push das tags. Anunciar no mesmo minuto (post de comunidade + card do trailer + latesconcept.com).
6. **28/11**: ativar GitHub Pages no repo `latesconcept` (main branch) → latesconcept.github.io com o mapa navegável.
7. Zenodo: registrar a v1.0 com DOI usando CITATION.cff + o zip da tag (login do autor).
Regra: nada se edita por cima após a tag — correção vai em commit novo.
