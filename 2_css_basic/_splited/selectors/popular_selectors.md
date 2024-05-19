електор	Приклад	Пояснення до прикладу
active	a:active	
Вибірка активного посилання.
--- 
adjacent	div + p	
Обирає елемент <p> який розташовується одразу за елементам <div>.
---
after	p::after	
Додає що-небудь після контенту елемента <p>
---

all	*	
Обирає всі елементи
---

attribute	[target]	
Обирає всі елементи, у котрих вказано атрибут target.
---

attribute-value	target="_blank"	
Обирає всі елементи з target="_blank"
---

attribute-value-begin	a[href^="https"]	
Обирає всі елементи <a> в яких значення атрибута href починається з "https".
---

attribute-value-contain	a[href*="w3schools"]	
Обирає всі посилання в яких атрибут href містить слово "w3schools".
---

attribute-value-contains	[title~=flower]	
Обирає всі елементи з атрибутом title в яких міститься слово flower
---

attribute-value-end	a[href$=".pdf"]	
Обирає всі елементи <a> в яких значення атрибута href закінчується рядком ".pdf"
---

attribute-value-lang	[lang|=en]	
Обирає всі елементи з атрибутом lang значенням якого починається з "en".
---

before	p::before	
Додає що-небудь перед контентом елемента <p>
---

checked	input:checked	
Обирає кожний елемент <input> який має значенняі checked.
---

class	.intro	
Вибірка всіх елементів з класом "intro".
---

default	input:default	
Обирає елемент введення форми, що без задання.
---

disabled	input:disabled	
Обирає всі вимкнені елементи введення.
---

element	p	
Обирає всі елементи <p>.
---

element-child	div > p	
Обирає всі елементи <p> для яких батьківським елементом є елемент <div>.
---

empty	p:empty	
Обирає кожен елемент <p> без тексту та інших HTML елементів.
---

enabled	input:enabled	
Обирає всі увімкнені елементи введення.
---

first-child	p:first-child	
Селектор :first-child обирає всі елементи <p>, які є першим нащадком свого батька.
---

first-letter	p::first-letter	
Обирає першу літеру кожного елементу <p>.
---

first-line	p::first-line	
Обирає перший рядок кожного елементу <p>
---

first-of-type	p:first-of-type	
Обирає елемент <p>, якщо він перший елемент свого батька.
---

focus	input:focus	
Обирає елемент <input>, який є у фокусі
---

hover	a:hover	
Обирає посилання на яке наведено курсор.
---

id	#firstname	
Вибирає елемент з ідентифікатором id="firstname"
---

in-range	input:in-range	
Обирає елементи <input> із значенням, що знаходяться в дозволеному діапазоні.
---

inside-element	div p	
Обирає всі елементи <p> в елементі <div>
---

invalid	input:invalid	
Обирає всі елементи input зі значенням, що не пройшло перевірки.
---

lang	p:lang(it)	
Обирає кожен елемент <p> з атрибутом lang у значенні "it" (Italian)
---

last-child	p:last-child	
Обирає елемент <p>, який є останнім нащадком свого батька.
---

last-of-type	p:last-of-type	
Обирає останній елемент свого батька.
---

link	a:link	
Обирає всі посилання по яким ще не переходили.
---

multielement	div, p	
Обирає всі елементи <div> і всі елементи <p>.
---

not	:not(p)	
Вибірка елементів, котрі не містять вказаний селектор.
---

nth-child	p:nth-child(2)	
Обирає елемент <p>, якщо він другий елемент свого батька.
---

nth-last-child	p:nth-last-child(2)	
Обирає кожен елемент <p>, що є другим нащадком свого батька починаючи відлік з кінця.
---

nth-last-of-type	p:nth-last-of-type(2)	
Обирає кожен елемент <p>, що є другим елементом <p> свого батька з кінця.
---

nth-of-type	p:nth-of-type(2)	
Вибирає кожен елемент <p>, що є другим <p> елемент свого батька.
---

only-child	p:only-child	
Вибирає елемент <p>, якщо він є єдиним нащадком свого батька.
---

only-of-type	p:only-of-type	
Обирає кожен елемент <p>, що є єдиним елементом <p> такого типу свого батька.
---

optional	input:optional	
Вибірка елементів <input>, що без атрибута "required".
---

out-of-range	input:out-of-range	
Вибірка всіх <input> елементів у котрих введене значення вийшло за межі дозволеного діапазону.
---

placeholder	input[type="text"]::placeholder	
Змінює стиль підсказки текстового поля <input>.!
---

read-only	input:read-only	
Обирає <input> елементи, котрі з атрибутом "readonly".
---

read-write	input:read-write	
Вибирає <input> елементи у яких не вказаний "readonly" атрибут.
---

required	input:required	
Вибірка елементів <input>, що обов'язкові для заповнення.
---

root	:root	
Вибирає кореневий елемент документа
---

selection	::selection	
Вибірка виділеного користувачем тексту.
---

sibling	p ~ ul	
Обирає всі елементи <ul> які розташовані після елементом <p>
---

target	#news:target	
Обирає поточний активний елемент, що має значення атрибута id="news"
---

valid	input:valid	
Обирає всі елементи введення з допустим значенням.
---

visited	a:visited	
Обирає посилання, по яким вже було здійснено перехід