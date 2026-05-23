# Nosso Cantinho

Site romantico estatico para publicar fotos e mensagens do casal usando GitHub Pages.

## Como editar

- Troque os textos em `index.html`.
- Para usar suas fotos, coloque os arquivos em uma pasta chamada `fotos` e altere o `src` das imagens da galeria. Exemplo: `src="fotos/minha-foto.jpg"`.
- O visual principal fica em `styles.css`.

## Publicar no GitHub Pages

1. Crie um repositorio no GitHub, por exemplo `nosso-cantinho`.
2. No terminal, dentro desta pasta, rode:

```bash
git init
git config user.name "jaaoopedroport-star"
git config user.email "jaaoopedroport@gmail.com"
git add .
git commit -m "Cria site romantico"
git branch -M main
git remote add origin https://github.com/jaaoopedroport-star/nosso-cantinho.git
git push -u origin main
```

3. No GitHub, abra o repositorio, va em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`, depois salve.

Depois disso, o GitHub vai mostrar o link do site publicado.
