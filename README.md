
!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sidebar menu With Sub-menu</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header class="header">
      <nav class="navbar">
        <span class="open-menu">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="16">
            <g fill="#252a32" fill-rule="evenodd">
              <path d="M0 0h24v2H0zM0 7h24v2H0zM0 14h24v2H0z" />
            </g>
          </svg>
        </span>
        <h1><a href="./index.html" class="brand">Code With Random</a></h1>
        <div class="menu-wrapper">
          <ul class="menu">
            <li class="menu-block">
              <span class="close-buffee">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20">
                  <path
                    fill="#252a32"
                    fill-rule="evenodd"
                    d="M17.778.808l1.414 1.414L11.414 10l7.778 7.778-1.414 1.414L10 11.414l-7.778 7.778-1.414-1.414L8.586 10 .808 2.222 2.222.808 10 8.586 17.778.808z"
                  />
                </svg>
              </span>
            </li>
            <li class="menu-item">
              <a href="#" class="menu-link">Menu Item</a>
            </li>
            <li class="menu-item has-collapsible">
              <a href="#"><span></span>Menu Item </a>
              <ul class="menu-child">
                <li class="menu-child-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-parent-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-parent-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-item"><a href="#">Sub Menu Item</a></li>
              </ul>
            </li>
            <li class="menu-item has-collapsible">
              <a href="#"><span></span>Menu Item</a>
              <ul class="menu-child">
                <li class="menu-child-fruits"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-toys"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-hoodfriends"><a href="#">Sub Menu Item</a></li>
              </ul>
            </li>
            <li class="menu-item has-collapsible">
              <a href="#">Menu Item</a>
              <ul class="menu-child">
                <li class="menu-child-hood"><a href="#">Sub Menu Item</a></li>
                <li class="menu-child-item"><a href="#">Sub Menu Item</a></li>
                <li class="menu-fruit"><a href="#">Sub Menu Item</a></li>
                <li class="menu-bevarge"><a href="#">Sub Menu Item</a></li>
                <li class="menu-healthy vegi salad"><a href="#">Sub Menu Item</a></li>
              </ul>
            </li>
            <li class="menu-item has-collapsible">
              <a href="#"><span></span>Menu Item</a>
              <ul class="menu-child">
                <li class="menu-nutrition"><a href="#">Sub Menu Item</a></li>
                <li class="menu-vegetable soap"><a href="#">Sub Menu Item</a></li>
                <li class="menu-musley"><a href="#">Sub Menu Item</a></li>
                <li class="menu-ice cream"><a href="#">Sub Menu Item</a></li>
                <li class="menu-oats"><a href="#">Sub Menu Item</a></li>
              </ul>
            </li>
            <li class="menu-item">
              <a href="#" class="menu-link">Menu Item</a>
            </li>
            <li class="menu-item">
              <a href="#" class="menu-link">Menu Item</a>
            </li>
          </ul>
        </div>
      </nav>
    </header>
    <section>
      <img
        src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
      />
    </section>
    <script src="index.js"></script>
  </body>
</html>
