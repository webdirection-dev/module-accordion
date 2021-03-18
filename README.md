# module-accordion
Скрипт для коллапсара.


## Подключение модуля
В данном репозитории точкой входа ___Webpack___ является _./src/js/script.js_.
<br /> Импортируем в него модуль со скриптом слайдера:
```javascript
import accordionJS from "./modules/accordionJS";

window.addEventListener('DOMContentLoaded', () => {
    'use strict';
    accordionJS('.accordion-heading');
});
```

 
