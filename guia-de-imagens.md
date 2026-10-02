# Guia de Imagens - Portal Express

Abaixo está a lista completa de imagens e placeholders utilizados no projeto. Você deve criar as imagens nos tamanhos recomendados e salvá-las na pasta `dist/assets/img/` antes de enviar os arquivos para a Hostinger.

## Tabela de Imagens Necessárias

| Arquivo | Seção | Tamanho Recomendado | Formato | Descrição |
|---------|-------|---------------------|---------|-----------|
| `favicon-32x32.png` | Meta tags (head) | 32x32px | PNG | Ícone principal para abas do navegador |
| `favicon-16x16.png` | Meta tags (head) | 16x16px | PNG | Ícone menor para abas do navegador |
| `apple-touch-icon.png` | Meta tags (head) | 180x180px | PNG | Ícone para dispositivos Apple / iOS |
| `logo.png` | Menu Principal | ~ 200x60px | PNG (Transparente) | Logotipo principal com versão clara ou colorida para fundo branco |
| `logo-reduzida.png` | Footer | ~ 150x40px | PNG (Transparente) | Logotipo para fundo escuro (rodapé) |
| `hero-bg.webp` | Hero (Início) | 1920x1080px | WebP / JPG | Foto principal do negócio, fundo escuro para destacar o texto branco |
| `cta-bg.webp` | CTA Final | 1920x800px | WebP / JPG | Foto para o fundo da seção de contato final |
| `sobre.webp` | Quem Somos | 800x600px | WebP | Foto da equipe, forno de pizza ou ambiente interno |
| `servico-esfihas.webp` | Cardápio | 600x400px | WebP | Foto atraente de esfihas frescas (abertas ou fechadas) |
| `servico-pizzas.webp` | Cardápio | 600x400px | WebP | Foto de pizza saindo do forno ou bem recheada |
| `servico-lanches.webp` | Cardápio | 600x400px | WebP | Foto de um hambúrguer artesanal ou lanche apetitoso |
| `servico-salgados.webp` | Cardápio | 600x400px | WebP | Foto de salgados variados fritos e/ou assados |
| `servico-doces.webp` | Cardápio | 600x400px | WebP | Foto de esfiha doce de chocolate ou outra sobremesa |

---

## Observações Importantes (Placeholders Manuais)

- **Iframe do Google Maps**: No HTML gerado (`dist/index.html`), busque pela seção `Onde Estamos e Regiões de Delivery`. Você encontrará uma div comentada informando `<!-- Placeholder para Google Maps iFrame -->`. Substitua o bloco correspondente pelo código do iFrame gerado diretamente no Google Maps.
- **Fallbacks (Imagens Padrão)**: Todos os elementos de imagem `<img src="...">` no HTML possuem a propriedade `onerror="this.src='https://placehold.co/...'"` para que o layout não quebre antes de você subir as fotos reais. Assim que as fotos forem enviadas para a pasta `assets/img/`, os placeholders serão automaticamente substituídos pelas suas imagens locais.
