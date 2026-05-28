# Maell J | Link in Bio

Página de links do DJ e produtor Maell J, reunindo playlists, perfis e redes sociais em um único endereço.

## Links

- Playlist Só o Molho! — Spotify
- SoundCloud
- TikTok
- Instagram

## Tecnologias

- HTML5 e CSS3
- Google Fonts (Sora + Open Sans)

## Estrutura

```
/
├── index.html
├── style.css
└── images/
    ├── profile-MaellDJ.jpg
    ├── spotify.png
    ├── soundcloud.png
    ├── tiktok.png
    └── instagram.png
```

## Como rodar

Abra o `index.html` no navegador. Não há dependências para instalar.

## Adicionar novos links

Insira um novo `<li>` dentro da `<ul class="list">` no `index.html`:

```html
<li class="list-item">
  <a class="link" target="_blank" href="URL">
    Nome da plataforma
    <img src="/images/logo.png" alt="Plataforma">
  </a>
</li>
```

---

Desenvolvido por Guilherme D'antoni.
