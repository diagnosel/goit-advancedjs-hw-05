# goit-advancedjs-hw-05

Тема 9. Вступ до TypeScript. Приклад із двома модулями: кнопка **Concat!**
поєднує введене слово з `hello!` і виводить результат у консоль браузера.

Потрібен Node.js 22 або новіший.

```bash
npm ci
npm start
```

Відкрити http://127.0.0.1:8000. `npm start` спочатку компілює TypeScript.

```bash
npm run build
npm run typecheck
npm run watch
```

`src/` містить вихідні `.ts`, `dist/` — згенеровані `.js` та `.js.map`.
Для автоматичної компіляції після змін запустити `npm run watch` в іншому терміналі.
У DevTools → Sources відкрити `src/concatenation.ts`, поставити breakpoint
на `console.log` та натиснути **Concat!**.
