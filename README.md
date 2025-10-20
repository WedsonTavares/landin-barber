
  <h2 align="center">Barbearia — Landing Page</h2>

  Página de demonstração totalmente responsiva para uma barbearia. Desenvolvida com HTML, CSS e JavaScript.

  <a href="https://wedsontavares.github.io/landin-barber/" target="_blank" rel="noopener"><strong>➥ Ver Demonstração</strong></a>

</div>


<h1 align="center">Barbearia — Landing Page (Frontend)</h1>

Este projeto é uma landing page para uma barbearia.

---

## Sumário

- [Demonstração](#demonstra%C3%A7%C3%A3o)
- [Screenshots](#screenshots)
- [Recursos](#recursos)
- [Como rodar localmente](#como-rodar-localmente)
- [Commit & Push (passo a passo)](#commit--push-passo-a-passo)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Contribuição](#contribui%C3%A7%C3%A3o)
- [Contato](#contato)
- [Licença](#licen%C3%A7a)

---


## Demonstração

Abra `index.html` diretamente no navegador ou rode um servidor estático local para testar.

Se quiser publicar, recomendo usar o GitHub Pages (branch `main` ou `gh-pages`).


Visualizar Demo: <a href="https://wedsontavares.github.io/landin-barber/" target="_blank" rel="noopener">https://wedsontavares.github.io/landin-barber/</a>

Repositório: <a href="https://github.com/WedsonTavares/landin-barber" target="_blank" rel="noopener">https://github.com/WedsonTavares/landin-barber</a>


---

## Screenshots

As imagens de demonstração estão em `readme-images/`. Aqui estão previews:

![Barber Desktop Demo](readme-images/desktop-demo.png)

> Observação: se as imagens não aparecerem, verifique se os arquivos existem em `readme-images/` e têm os nomes corretos.

---

## Recursos

- Layout totalmente responsivo
- Hero com imagem que se adapta para exibir a imagem inteira em diferentes tamanhos
- Filtro de preços por categoria
- Formulário de agendamento (front-end)
- Ano do rodapé atualizado automaticamente via JavaScript

---

## Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/WedsonTavares/landin-barber.git
cd landin-barber
```

2. Abra `index.html` no navegador ou rode um servidor estático (recomendado):

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

3. Para desenvolver, edite `index.html`, `assets/css/style.css` e `assets/js/script.js`.

---

## Commit e Push — passo a passo

Use estes comandos para commitar e enviar as alterações ao remoto (assume a branch `main`):

```bash
# 1) conferir status
git status

# 2) adicionar arquivos alterados
git add .

# 3) commitar com mensagem clara
git commit -m "Tradução pt-BR: textos, contatos e preços; ajustes CSS/JS"

# 4) enviar para o repositório remoto
git push origin main
```

Se precisar trocar a URL do remoto:

```bash
git remote remove origin
git remote add origin https://github.com/WedsonTavares/landin-barber.git
git push -u origin main
```

---

## Estrutura do projeto

- `index.html` — página principal (texto em pt-BR)
- `index.txt` — referência com todos os textos do site (pt-BR)
- `assets/css/style.css` — estilos (ajustes para hero, preços, rodapé)
- `assets/js/script.js` — comportamento (navbar, filtro, ano automático)
- `readme-images/` — imagens usadas no README

---

## Contribuição

1. Faça um fork
2. Crie uma branch: `git checkout -b minha-mudanca`
3. Faça alterações e commite
4. Abra um Pull Request

---

## Contato

- LinkedIn: <a href="https://www.linkedin.com/in/wedsontavares/" target="_blank" rel="noopener">https://www.linkedin.com/in/wedsontavares/</a>
- Email: contato@barbeariaexemplo.com

---

## Licença

Projeto livre para estudo e uso pessoal. Inclua atribuição se compartilhar publicamente.

---
