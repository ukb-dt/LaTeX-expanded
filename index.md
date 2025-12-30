```js
<script>
window.MathJax = {
  tex: {
    inlineMath: [
      ['$', '$'],          // standard
      ['\\(', '\\)'],      // LaTeX inline
      ['\\[', '\\]'],      // sometimes misused inline
      ['\\{', '\\}'],      // rare but seen
      ['`$', '$`']         // defensive: malformed markdown
    ],
    displayMath: [
      ['$$', '$$'],        // standard display
      ['\\[', '\\]'],      // LaTeX display
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
    skipHtmlTags: [
      'script',
      'noscript',
      'style',
      'textarea',
      'pre',
      'code'
    ]
  }
};
</script>

```
