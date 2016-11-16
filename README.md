# Монте Карло изчисления с Python


## Съобщения

### Първото контролно ще се проведе на 23.11.2016 от 18:15 часа. Ще е 1 час. В него ще се включва взет до 7-мата седмица включително. 
Който не е присъствал може да потърси записки от колегите, а също да разгледа алгоритмите качени в репозиторито.

### Домашни

Домашни предадени след срока ще получат 50% от точките, с които са оценени. Изключение е само първото домашно.

- ### Срокът за [четвъртото домашно]() е до 30.11.2016
- ### Срокът за [третото домашно]() е до 23.11.2016
- ### Срокът за [второто домашно](https://bitbucket.org/montebianco/mccpy/src/8a21d1bc594ccd29dd3aef853a5e7d4ccbfe740a/week5/homework_2/?at=master) е до 16.11.2016
- ### Срокът за [първото домашно](https://bitbucket.org/montebianco/mccpy/src/9ea1b1b665a6c8d195de4c6256ea124b317acded/week2*4/homework_1/?at=master) e до 9.11.2016



## Примерни теми за курсова работа

Приемливо е всяко приложение на Монте Карло метод в проблем, който ви интересува. Курсовата работа трябва да съдържа
1. Описание на задачата.
2. Монте Карло решение
3. Оценка на грешката и поведение на алгоритъма

 - каква е теоретическата грешка какво е поведението при увеличаване на входните параметри?
 - каква е практическата наблюдавана грешка и приемлива ли е?
 - какво е времето за изпълнение спрямо различни входни данни?
 - сравнение на алгоритъма с друг подход.
 
Курсовия проект ще се счита за успешен дори ако Монте Карло алгоритъма не е по-добър от детерминистичния, с който го сравнявате.

Ако все пак се затруднявате да си изберете тема, ето няколко насоки:

 - Прилагане на Монте Карло алгоритъм към комбинаторна или друга оптимизационна задача. Например [TSP](https://en.wikipedia.org/wiki/Travelling_salesman_problem), но не точно този, защото него ще разгледаме в час.
 - Оценяване на финасови инструменти с МК сумулация [MKF](https://en.wikipedia.org/wiki/Monte_Carlo_methods_in_finance)
 - Интегриране на сложен интеграл, например такъв, който представлява осветеността на обект.
 - Симулация на флуид или какъв да е друг процес от природата, в който има случайно поведение.
 - Анализ на данни, в които обучението се извършва с МК алгоритъм, [например](http://nbviewer.jupyter.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter3_MCMC/Ch3_IntroMCMC_PyMC2.ipynb)

## Въведение

В това репозитори ще се публикуват програмите, които ще използваме по време на лекциите и упражненията. Всяка седмица ще има отделена директория.
Голяма част от курса и качените програми са от курса на проф. Краут [Statistical Mechanics: Algorithms and Computations](https://www.coursera.org/learn/statistical*mechanics). От книгата със същото име ще ползваме първа и седма глава. Тя може лесно да се намери в интернет.
Ще ползваме пакетите на Python за научни изследвания numpy, scipy и pymc3. Повече за тях може да намерите на [SciPy.org](https://www.scipy.org/).

За да си набавите нужните пакети и Python 3, може да ползвате [Anaconda](https://www.continuum.io/downloads).

За IDE може да ползвате [PyCharm](https://www.jetbrains.com/pycharm/), Eclipse+PyDev или каквото ви е удобно.


## Оценяване

Ще има: 

- 5 домашни по 10 точки.
- 3 контролни по 50 точки.
- 1 курсов проект по 100 точки.

Общо 300 точки. Ако съберете повече от 220 точки получавате 6. При повече от 190: 5, повече от 150: 4, повече от 120: 3.


## Програма по седмици

1. Въведение в изчислителното програмиране с Python
2. Монте Карло(МК) методи: директна извадка (Direct sampling), Марковска верига Монте Карло (Markov chain Monte Carlo)(MCMC)
3. Случайни числа. Вероятностни разпределения, Централна гранична теорема
4. Оценка на грешката на МК методи, корелация в MCMC
5. Симулация на твърди дискове(статистическа механика) 
6. Ентропични взаимодействия, статистическа сума
7. Случайни числа върху и в сфера. Разпределение на Максуел. Интегриране в голяма размерност
8. Интегриране на по-сложни разпределения. Намаляване на вариацията, приоритетни извадки (importance sampling)
9. Оптимизация с МК- симулирано охлаждане
10. Други вероятностни оптимизационни алгоритми
11. Приложения в Бейсови оценки с пакета pymc3
12. Примери с pymc3
13. +курсови работи