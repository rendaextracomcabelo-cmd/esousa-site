# esousa-site

Site oficial da E Sousa Serviços Digitais — https://esousa.com.br

## Caminhos

| Endereço | O que abre | Onde fica |
|---|---|---|
| `/` | Página principal | `index.html` deste repositório |
| `/arte-e-papel` | E Sousa Arte & Papel | pasta `arte-e-papel/` deste repositório |
| `/agenteisa` | Isa | rewrite para `agente-isa.vercel.app` |
| `/agentedetopobelaisa` | Belaisa | rewrite para `belaisa.vercel.app` |
| `/links` | Link da bio (fora do Google) | rewrite + cabeçalho `noindex` |

## Pendências

- [ ] `vercel.json`: trocar `LINKS-PROJETO` pelo endereço .vercel.app real da página de Links
- [ ] Ao criar um produto novo: adicionar o rewrite no `vercel.json`, o link no `index.html` e a linha no `sitemap.xml`
