# Spartan Academia

Landing page da Spartan Academia, academia em Votuporanga - SP com 2 unidades.

- Unidade I: Rua São Paulo, 4211
- Unidade II: Rua Ângelo Bimbato, 3188

Site estático: só HTML, CSS e JavaScript, sem build e sem dependências externas. Hospedado na Vercel.

## Estrutura

```
index.html        página completa
vercel.json       cabeçalhos de segurança usados pela Vercel
assets/           fotos, logo e fonte usadas pela página
  fonts/          fonte Oswald (licença OFL em OFL-LICENSE.txt)
```

## Publicar na Vercel

1. Na Vercel, clique em **Add New > Project** e importe este repositório.
2. Em **Framework Preset**, deixe **Other**. Não há comando de build nem pasta de saída a configurar.
3. Clique em **Deploy**. A cada push na branch `main`, a Vercel publica a nova versão sozinha.

## Atualizar conteúdo

- **Fotos:** substitua o arquivo em `assets/` mantendo o mesmo nome (WebP ou JPG, 960 a 1440 px de largura). A foto do topo tem duas versões: `hero-fachada-unidade-2.webp` (computador) e `hero-fachada-unidade-2-800.webp` (celular).
- **Preços:** no fim do `index.html`, edite o objeto `PRICES` e também os valores iniciais dos cards na seção `PLANOS`.
- **Links de checkout:** objeto `CHECKOUT` no fim do `index.html`.
