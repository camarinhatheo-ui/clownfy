# Clownfy

Agência de social media e sites. Instagram: [@agenciaclownfy](https://instagram.com/agenciaclownfy)

## O que tem aqui

| Pasta | Conteúdo |
|---|---|
| `site/` | Site da agência (página única em `index.html`), com imagens em `site/img/` e som em `site/audio/` |
| `site/instagram/` | Posts do Instagram: o HTML de cada arte e o PNG final (1080×1350) |
| `portfolio/` | Trabalhos de exemplo (Pizzaria Brasa Alta, Barbearia Navalha Norte, Loja Maré): logos, posts, stories e resumos |
| `kiwify/` | Imagens dos produtos na Kiwify (capas, checkout, ingressos e plaquinhas dos planos Essencial, Profissional e Premium) |
| `producao/` | Planilha de produção |
| raiz | Fotos de perfil do Instagram (`clownfy-perfil.png`, `clownfy-perfil-logo.png`) |

## Ver o site no computador

Na pasta `site`, rode:

```bash
python -m http.server 5500
```

e abra http://localhost:5500.

## Gerar o PNG de um post

Abra o HTML do post (por exemplo `site/instagram/post-01.html`) no Chrome com a janela em 1080×1350, ou rode o Chrome em modo headless:

```bash
chrome --headless=new --hide-scrollbars --window-size=1080,1350 --screenshot=post-01.png site/instagram/post-01.html
```
