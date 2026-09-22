# G+SOMA — Landing Pages

Páginas de vendas da G+SOMA (Saúde e Segurança do Trabalho). São páginas estáticas em HTML, sem dependências de build.

## Campanhas

| Pasta | Campanha | URL |
|---|---|---|
| `nr01/` | Adequação à NR-01 e riscos psicossociais | [/gsoma-lps/nr01/](https://alanpeixotocontieri.github.io/gsoma-lps/nr01/) |
| `pgr-pcmso/` | PGR e PCMSO | [/gsoma-lps/pgr-pcmso/](https://alanpeixotocontieri.github.io/gsoma-lps/pgr-pcmso/) |
| `exames-aso/` | Exames ocupacionais e ASO | [/gsoma-lps/exames-aso/](https://alanpeixotocontieri.github.io/gsoma-lps/exames-aso/) |

Cada pasta contém:

```
<campanha>/
├── index.html                    CSS e JS embutidos, sem dependências
└── assets/
    ├── logo-gsoma.png            versão preta — cabeçalho (fundo claro)
    ├── logo-gsoma-branca.png     versão branca — rodapé (fundo preto)
    └── img/                      imagens da campanha
```

## Identidade visual

Conforme o Manual de Marca G.Soma.

| Cor | Hex | Uso |
|---|---|---|
| Vermelho | `#DB051E` | CTAs, destaques, links |
| Vermelho escuro | `#BA001B` | hover dos botões, barra de alerta |
| Preto | `#000000` | fundos escuros, rodapé, títulos |
| Branco | `#FFFFFF` | fundos claros, texto sobre escuro |

**Tipografia:** Plus Jakarta Sans (Google Fonts), pesos 400 a 800.
A fonte não possui peso 900 — usar no máximo 800 para evitar negrito sintético.

**Logo:** assinatura horizontal completa (símbolo + "SAÚDE E SEGURANÇA DO TRABALHO").
Os arquivos originais em SVG, PNG, EPS e AI estão na pasta `IDENTIDADE VISUAL`, fora do repositório.

## Como publicar

O GitHub Pages está configurado em **Settings → Pages**, publicando da branch `main`, pasta `/ (root)`.

Cada commit na `main` republica o site em cerca de 1 minuto.

## Como alterar uma página

1. Abrir o `index.html` da campanha
2. Clicar no ícone de lápis (**Edit this file**)
3. Alterar e clicar em **Commit changes**

Para trocar arquivos (imagens, logo), usar **Add file → Upload files** dentro da pasta de destino. Arquivos com o mesmo nome são substituídos; os demais permanecem intactos.

Após publicar, abrir com **Cmd+Shift+R** — o navegador guarda imagens em cache e pode mostrar a versão antiga.

Se a página já estiver recebendo tráfego pago, alterar em uma branch separada e fazer o merge depois de conferir.

## Pendências antes de anunciar

- [ ] Integrar o formulário ao CRM (ver o comentário `>>> INTEGRAÇÃO` no final de cada `index.html`)
- [ ] Substituir telefone, e-mail e endereço pelos dados reais da G+SOMA
- [ ] Trocar os depoimentos ilustrativos pelos reais
- [ ] Substituir as imagens de banco por fotos próprias da estrutura e da equipe
- [ ] Confirmar a licença das imagens atuais antes de veicular
- [ ] Validar com o comercial a promessa de retorno "em até 1 dia útil"
- [ ] Validar as alegações sobre implementadores reconhecidos pelo MEC e pioneirismo na região
- [ ] Instalar Google Tag Manager / Analytics e configurar a conversão
