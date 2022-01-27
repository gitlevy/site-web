# Doculentation

*   Installation
*   Mise en place
*   Commit


```

  function createEl(type, className, parentEl) {
    var el = document.createElement(type);
    if (className) el.classList.add(className);
    if (parentEl) parentEl.appendChild(el);
    return el;
  }
  
  ```
