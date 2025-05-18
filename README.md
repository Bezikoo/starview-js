# StarView.js

StarView.js — це легкий JavaScript Web-фреймворк для фронтенд-розробки. Він підтримує компонентну структуру, реактивність і швидке з’єднання з DOM. Ідеально підходить для створення сучасних вебзастосунків.

##  Встановлення

Встановити через npm:

```bash
npm install starview
```

Або використати CDN:

```html
<script src="https://cdn.starviewjs.org/latest/starview.min.js"></script>
```

##  Використання

```javascript
import { createApp } from 'starview';

const App = {
  data() {
    return {
      message: 'Привіт, світ!'
    };
  },
  template: `<h1>{{ message }}</h1>`
};

createApp(App).mount('#app');
```

```html
<div id="app"></div>
```

##  Розробники

- Іващенко Гліб— головний розробник
- Іващенко Гліб— технічна документація
##  Документація


##  Ліцензія

Цей проєкт поширюється за ліцензією MIT.  
Дивіться файл [LICENSE](./LICENSE).
