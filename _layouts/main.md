<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web development</title>
    <link rel="stylesheet" href={{ "/style.css" | relative_url}}>
  </head>

  <body>
    {% include navbar.md %} 
    {% include sidebar.md side=page.side nav=page.nav %}
    {{ content }}
  </body>
</html>
