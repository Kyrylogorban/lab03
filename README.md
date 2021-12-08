# lab03
абораторна робота №3. Розробка лінійних програм

Горбань Кирило,  КІТ-121д

Підрахувати суму чисел у заданому діапазоні. Наприклад, при вхідних даних 50 та 52
повинно бути 50 + 51 + 52 = 153.

Основна частина:
- описать роботи основної функції: розраховується за формулою суми членів арефмитичної прогресії s=((a1=an)*n)/2
- перелік вхідних даних:
   - a1 - перше число, позитивне дійсне число (float);
   - an - друге число, позитивне дійсне число (float).
   - n - кількість усіх чисел, позитивне дійсне число (float).
   - s - сумма чисел у задаому діапазоні, позитивне дійсне число (float).

- исследование результатов роботов программирования:
   - s - сумма чисел у задаому діапазоні Так як всі оперуємі числа єдійсними, то й особуюча змінна є дійсною. Також, слід визначити, що сумма чисел у задаому діапазоні не може бути негативним. Тому, її тип - поплавок
   - при значенні a1 = 10 та an = 12, сумма чисел у задаому діапазоні повинa складати: 10+11+12=33
   - для підтвердження коректності роботи програми, зупинен відлагодник на строцы с "return 0" и введемо команду "print s". Після вводу команди отримали наступне:
	(lldb) print s
	 $ 1 = 33

Структура проекту лабораторної роботи:

	.
	└── lab03
	    ├── README.txt
	    ├── Makefile
	    └── src
	        └── main.c

Висновки: при виконанні лабораторної роботи буди набуті практичні навички створення лінійних программ на мові С, зокрема: назначить тип данных, обчислювати математические вирази, емулювати операцію зведення до ступеню через операцію мненю.
