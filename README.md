# G-Soma — Landing Pages

Páginas de vendas da G-Soma (Medicina e Segurança do Trabalho). São páginas estáticas em HTML, sem dependências de build.

## Campanhas

| Pasta | Campanha | URL após publicar |
|---|---|---|
| `nr01/` | Adequação à NR-01 e riscos psicossociais | `/gsoma-lps/nr01/` |
| `pgr-pcmso/` | PGR e PCMSO | `/gsoma-lps/pgr-pcmso/` |
| `exames-aso/` | Exames ocupacionais e ASO | `/gsoma-lps/exames-aso/` |

Cada pasta tem um `index.html` autossuficiente (CSS e JS embutidos) e uma pasta `assets/` com a logo.

## Como publicar no GitHub Pages

1. No repositório, abrir **Settings** → **Pages**
2. Em *Source*, escolher **Deploy from a branch**
3. Selecionar a branch `main` e a pasta `/ (root)`
4. Salvar e aguardar cerca de 1 minuto

A URL fica no formato `https://SEU-USUARIO.github.io/gsoma-lps/nr01/`.

## Como alterar uma página depois de publicada

1. Abrir o arquivo `index.html` da campanha no GitHub
2. Clicar no ícone de lápis (**Edit this file**)
3. Fazer a alteração e clicar em **Commit changes**
4. O site republica sozinho em cerca de 1 minuto

Se a página já estiver recebendo tráfego pago, é mais seguro editar em uma branch separada e fazer o merge depois de conferir.

## Pendências antes de anunciar

- [ ] Integrar o formulário ao CRM (procurar o comentário `>>> INTEGRAÇÃO` no final de cada `index.html`)
- [ ] Substituir telefone, e-mail e endereço pelos dados reais da G-Soma
- [ ] Trocar os depoimentos ilustrativos pelos reais
- [ ] Inserir fotos da estrutura, da equipe e logos de clientes
- [ ] Validar com o comercial a promessa de retorno "em até 1 dia útil"
- [ ] Instalar o Google Tag Manager / Analytics e configurar a conversão

## Identidade visual

| Cor | Hex |
|---|---|
| Verde | `#31893C` |
| Laranja | `#EF7700` |
| Azul | `#3070B8` |
| Branco | `#FFFFFF` |

Fonte: Inter (Google Fonts).
