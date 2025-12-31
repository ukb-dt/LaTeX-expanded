```js
{% raw %}
<script>
window.MathJax = {
  tex: {
    inlineMath: [
      ['$', '$'],
      ['\\(', '\\)']
    ],
    displayMath: [
      ['$$', '$$'],
      ['\\[', '\\]'],
      ['\\begin{equation}', '\\end{equation}'],
      ['\\begin{align}', '\\end{align}'],
      ['\\begin{aligned}', '\\end{aligned}'],
      ['\\begin{gather}', '\\end{gather}'],
      ['\\begin{multline}', '\\end{multline}'],
      ['\\begin{eqnarray}', '\\end{eqnarray}'],
      ['\\begin{cases}', '\\end{cases}'],
      ['\\begin{split}', '\\end{split}']
    ],
    processEscapes: true,
    processEnvironments: true
  },
  options: {
    skipHtmlTags: ['script', 'noscript', 'style', 'textarea', 'pre', 'code']
  }
};
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
{% endraw %}
```
