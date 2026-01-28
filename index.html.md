<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Zettel Garden</title>

  <!-- Docsify -->
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/vue.css">

  <!-- Plugin wikilinks -->
  <script src="https://cdn.jsdelivr.net/npm/docsify-plugin-wikilinks"></script>
</head>
<body>
  <div id="app">Loading...</div>
  <script>
    window.$docsify = {
      name: 'Zettel Garden',
      repo: '',               // opzionale, link al repo GitHub
      loadSidebar: true,      // abilita la sidebar
      subMaxLevel: 2,         // massimo livello dei titoli
      markdownIt: window.markdownit(),
      plugins: [
        window.DocsifyWikiLinks()
      ]
    }
  </script>
</body>
</html>
