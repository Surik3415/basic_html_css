в html можна міксувати блоки і елементи

елемент може бути і самостійнм блоком. розміщувати елементи можна на кожному рівні вкладеності.
Приклад:

<aside class="aside">
    <nav class="about__nav">
      <ul class="aside__list list">
        <li class="list__item">Text_1</li>
        <li class="list__item">Text_2</li>
        <li class="list__item">Text_3</li>
      </ul>
  </nav>
</aside>

тут ul є частиною блоку aside як модифікатор, а також самостійно виступає блоком для айтемів


