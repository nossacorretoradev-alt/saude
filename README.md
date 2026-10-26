# Nossa Corretora · Simulador de planos (front)

Simulador público de planos de saúde **CDL Mossoró × Unimed**: o cliente
monta a cotação (titulares, dependentes e planos), confere se a empresa é
associada à CDL e, se for empresa nova, assina o contrato de associação.
A venda cai direto no Pipeline do portal.

No ar em **https://simulador.nossaapp.com.br** (GitHub Pages).

Link de vendedor: `https://simulador.nossaapp.com.br/index.html?v=CÓDIGO` —
a venda já chega com o vendedor responsável.

## Repositórios do sistema

| Repositório | O que é | Onde fica no ar |
|---|---|---|
| `portal` | Portal e páginas públicas do cliente | Cloudflare Pages · portal.nossaapp.com.br |
| `saude` (este) | Simulador | GitHub Pages · simulador.nossaapp.com.br |
| `nossa-backend` | Funções do Supabase, SQL e script do Google | Supabase |

## Arquivos

| Arquivo | Para quê |
|---|---|
| `index.html` | o simulador |
| `termos-de-uso.html` | termos de uso e participação |
| `formulario-cliente.html`, `documentos-cliente.html` | cópias antigas; os links enviados aos clientes hoje usam as versões do `portal` |
| `CNAME` | domínio do GitHub Pages |
