<div class="side-bar">
  <ul>
    <li class="nav-bar-item">
      <a {% if include.side contains "headings" %} class="active" {% endif %} href="./headings.html">Headings</a>
    </li>
    <li>
      <a {% if include.side contains "paragraphs" %} class="active" {% endif %} href="./paragraphs.html">Paragraphs</a>
    </li>
    <li>
      <a {% if include.side contains "links" %} class="active" {% endif %} href="./links.html">Links</a>
    </li>
    <li>
      <a {% if include.side contains "images" %} class="active" {% endif %} href="./images.html">Images</a>
    </li>
    <li>
      <a {% if include.side contains "lists" %} class="active" {% endif %} href="./lists.html">Lists</a>
    </li>
    <li>
      <a {% if include.side contains "tables" %} class="active" {% endif %} href="./tables.html">Tables</a>
    </li>
    <li>
      <a {% if include.side contains "forms" %} class="active" {% endif %} href="./forms.html">Forms</a>
    </li>
  </ul>
</div>