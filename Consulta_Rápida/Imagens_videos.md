# Como Inserir Mídias em Markdown

## 🖼️ Imagens

### Jeito simples
```markdown
![descrição da imagem](URL_ou_caminho_da_imagem)
```

### Controlando o tamanho — HTML
```html
<img src="URL_ou_caminho_da_imagem" width="400" />
```

### Centralizando
```html
<p align="center">
  <img src="URL_ou_caminho_da_imagem" width="400" />
</p>
```

---

## 🎞️ GIFs

GIFs funcionam exatamente como imagens:

```markdown
![demo](URL_ou_caminho_do_gif)
```

Ou com controle de tamanho:
```html
<img src="URL_ou_caminho_do_gif" width="600" />
```

> 💡 GIFs são ideais para loops curtos e animações de interface. Para demonstrações longas, prefira vídeo.

---

## 🎬 Vídeos

O Markdown puro não suporta vídeo nativamente. A solução é usar HTML:

```html
<video src="caminho/do/video.mp4" controls width="600"></video>
```

Ou com autoplay e sem controles:
```html
<video src="caminho/do/video.mp4" autoplay loop muted width="600"></video>
```

> ⚠️ O suporte à tag `<video>` depende do renderizador. Algumas plataformas (como o GitHub) ignoram essa tag — nesses casos, arraste o vídeo direto no editor e use o link gerado automaticamente.

---

## 📐 Dicas de Layout

### Imagens lado a lado — tabela
```markdown
| Antes | Depois |
|-------|--------|
| <img src="url1" width="300"/> | <img src="url2" width="300"/> |
```

### Usando caminhos relativos
Em vez de URLs, você pode referenciar arquivos locais:
```markdown
![demo](assets/minha-imagem.png)
```
