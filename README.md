# Temas do FORJA

Cada pasta é um tema. O FORJA lê `index.json` (lista das pastas) e mostra-os na página **Temas**.

```
<id>/tema.json      nome, autor, descrição, cores, imagem de fundo, opacidade, som
<id>/capa.jpg       imagem do cartão na galeria (640x360)
<id>/fundo.jpg      imagem de fundo da janela (opcional)
<id>/conquista.wav  som ao desbloquear uma conquista (opcional, WAV)
```

Cores aceites: Bg, Panel, Card, Hover, Line, LineStrong, Fg, Muted, Faint, Ink — `#RRGGBB` ou `#AARRGGBB`
(com transparência, para a imagem de fundo aparecer por trás dos painéis).

Para publicar um tema novo: criar a pasta, acrescentar o id ao `index.json` e enviar para o repositório Forja-Temas.
