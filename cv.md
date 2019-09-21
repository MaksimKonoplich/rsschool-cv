# rsschool-cv

1. **Maksim Konoplich**
2. Phone Number: +375295382436; email: gladiator8899@mail.ru; discord: Maksim Konoplich#2325
3. I want to be a _full-stack Web-Developer_, get knowledge and practice in _JavaScript_
4. **Skills**: [HTML5](https://ru.wikipedia.org/wiki/HTML5), [CSS3](https://ru.wikipedia.org/wiki/CSS), [JavaScript](https://ru.wikipedia.org/wiki/JavaScript), [Bootstrap 4.0](https://bootstrap-4.ru), Git.
5. 
```javascript
		function formatDate(date) {
			if (typeof date == 'number') {
				date = new Date(date * 1000);
			} else if (typeof date == 'string') {
				date = new Date(date); 
			} else if (Array.isArray(date)) { 
				date = new Date(date[0], date[1], date[2]);
			}
				return date.toLocaleString("ru", {day: '2-digit', month: '2-digit', year: '2-digit'}); 
		}

		alert( formatDate('2011-10-02') ); // 02.10.11
		alert( formatDate(1234567890) ); // 14.02.09
		alert( formatDate(new Date(2014, 0, 1)) ); // 01.01.14
```
```javascript
		function sumTo(n) {
			var result = 0;
			for (var i = 1; i < n; i++) {
				result += i;
			}
			return result;
		}
		alert( sumTo(100) );
```
6. [Blog](https://github.com/MaksimKonoplich)
7. Basics of algorithms and programming at the university, HTML and CSS on [htmlacademy.ru](https://htmlacademy.ru), **JavaScript**: documentation and Eric Freeman's "Learning programming on Javascript. Head First".
8. English Level: **B1**(Sertificate of foreign language School *"Streamline"*).