{% if include.nav == "HTML" %}

<div class="side-bar">
  <ul>
    <li class="nav-bar-item">
      <a {% if include.side contains "Headings" %} class="active" {% endif %} href="./headings.html">Headings</a>
    </li>
    <li>
      <a {% if include.side contains "Paragraphs" %} class="active" {% endif %} href="./paragraphs.html">Paragraphs</a>
    </li>
    <li>
      <a {% if include.side contains "Links" %} class="active" {% endif %} href="./links.html">Links</a>
    </li>
    <li>
      <a {% if include.side contains "Images" %} class="active" {% endif %} href="./images.html">Images</a>
    </li>
    <li>
      <a {% if include.side contains "Lists" %} class="active" {% endif %} href="./lists.html">Lists</a>
    </li>
    <li>
      <a {% if include.side contains "tables" %} class="active" {% endif %} href="./tables.html">tables</a>
    </li>
    <li>
      <a {% if include.side contains "forms" %} class="active" {% endif %} href="./forms.html">forms</a>
    </li>
  </ul>
</div>

{% endif %}

{% if include.nav == "CSS" %}

<div class="side-bar">
  <ul>
   <li class="nav-bar-item">
      <a {% if include.side contains "Syntax" %} class="active" {% endif %} href="./syntax.html">Syntax</a>
    </li>
    <li>
      <a {% if include.side contains "Selectors" %} class="active" {% endif %} href="./selectors.html">Selectors</a>
    </li>
    <li>
      <a {% if include.side contains "Colors" %} class="active" {% endif %} href="./colors.html">Colors</a>
    </li>
    <li>
      <a {% if include.side contains "Backgrounds" %} class="active" {% endif %} href="./backgrounds.html">Backgrounds</a>
    </li>
    <li>
      <a {% if include.side contains "Margins" %} class="active" {% endif %} href="./margins.html">Margins</a>
    </li>
    <li>
      <a {% if include.side contains "Sizes" %} class="active" {% endif %} href="./sizes.html">Sizes</a>
    </li>
    <li>
      <a {% if include.side contains "Texts" %} class="active" {% endif %} href="./texts.html">Texts</a>
    </li>
    <li>
      <a {% if include.side contains "Fonts" %} class="active" {% endif %} href="./fonts.html">Fonts</a>
    </li>
  </ul>
</div>

{% endif %}

{% if include.nav == "Javascript" %}

<div class="side-bar">
  <ul>
    <li class="nav-bar-item">
      <a {% if include.side contains "Syntax" %} class="active" {% endif %} href="./syntax.html">Syntax</a>
    </li>
    <li>
      <a {% if include.side contains "Variables" %} class="active" {% endif %} href="./variables.html">Variables</a>
    </li>
    <li>
      <a {% if include.side contains "Operators" %} class="active" {% endif %} href="./operators.html">Operators</a>
    </li>
    <li>
      <a {% if include.side contains "Data types" %} class="active" {% endif %} href="./data_types.html">Data types</a>
    </li>
    <li>
      <a {% if include.side contains "Functions" %} class="active" {% endif %} href="./functions.html">Functions</a>
    </li>
    <li>
      <a {% if include.side contains "Objects" %} class="active" {% endif %} href="./objects.html">Objects</a>
    </li>
    <li>
      <a {% if include.side contains "Events" %} class="active" {% endif %} href="./events.html">Events</a>
    </li>
    <li>
      <a {% if include.side contains "Conditions" %} class="active" {% endif %} href="./conditions.html">Conditions</a>
    </li>
    <li>
      <a {% if include.side contains "Loops" %} class="active" {% endif %} href="./loops.html">Loops</a>
    </li>
    <li>
      <a {% if include.side contains "RegExp" %} class="active" {% endif %} href="./regexp.html">RegExp</a>
    </li>
  </ul>
</div>

{% endif %}
