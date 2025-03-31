Скрипт `script.js`

```javascript
const toggleButton = document.getElementById('toggleButton');
const moreInfo = document.getElementById('moreInfo');

toggleButton.addEventListener('click', () => {
  if (moreInfo.style.display === 'none' || moreInfo.style.display === '') {
    moreInfo.style.display = 'block';
    toggleButton.textContent = 'Скрыть';
  } else {
    moreInfo.style.display = 'none';
    toggleButton.textContent = 'Показать больше';
  }
});
```