{% if page.htmlwidgets %}
{% for html_dep in site.static_files %}
  {% if html_dep.path contains 'htmlwidgets_deps/' %}
    {% assign start = "<script src=" | append: {{site.baseurl}} %}
    {{html_dep.path | prepend: start | append: "></script>" }}
    {% endif %}
  {% endfor %}
{% endif %}


<body>
    <h1>Geographically Weighted Linear Combination Test</h1>
  <h2>
        Significant Genesets for 5 phenotypes at Low, Medium and High CAF levels.
  </h2>
  
  <iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~mhajihos/66.embed"></iframe>
  <iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~mhajihos/62.embed"></iframe>
  <iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~mhajihos/60.embed"></iframe>
  <iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~mhajihos/58.embed"></iframe>
  <iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~mhajihos/56.embed"></iframe>
 

    <h2>The number of significant genesets for COL11A1 at high CAF level</h2>
      
   <iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~mhajihos/68.embed"></iframe>   
      
      <body>
