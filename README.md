Repo for the lab 5 of js-frameworks

Лабораторна робота №5
Тема: Основи роботи з компонентами. Шаблони. Директиви.
Мета: опанувати базові принципи створення та використання компонентів у Vue.js.
Ознайомитися з шаблонами в компонентах Vue. Навчитися використовувати основні
директиви Vue.js у шаблонах.
Вимоги до звіту:
1. Завдання 1 має бути виконане в окремій гілці (tutorial) github репозиторію студента
даної лабораторної роботи.
2. Завдання 2 - 5 має бути виконане в окремій гілці (users-app) github репозиторію студента
даної лабораторної роботи.
3. Файлова структура лабораторної роботи після merge гілок (lab-4/tutorial, lab-4/users-app).
Завдання:
1. Пройти весь tutorial https://ua.vuejs.org/tutorial/#step-1 (Стиль API: Композиційний, SFC).
Результат виконання кожного задання фіксувати у вигляді скріншоту з відповідним
неймінгом (step-1.(jpg|png)).
2. Створіть новий проект Vue 3 за допомогою vue-create.
◦ Виокристовуйте TypeScript з Композиційним API ( Add TypeScript? Yes). Що таке
Композиційний API: https://ua.vuejs.org/guide/extras/composition-api-faq.html
◦ Використовуйте Eslint (Add ESLint for code quality? Yes).
◦ Ознайомтесь з структурою стартового проекту.
◦ Під час написання застосунку, дотримуватись style guide - https://ua.vuejs.org/style-
guide/
3. Створіть простий компонент який буде мати наступну структуру:
◦ Шаблон з інформацією про користувача (firstName, lastName, gender, age, position,
photo, hobbies).
◦ Виведіть дані про користувача на ui (використовуйте об’єкт userData).
◦ Додайте стилі для картки користувача.
4. У шаблоні компонента юзера додайте:
◦ Використання директиви v-if, щоб показувати вік тільки якщо він більше 18 років.
◦ Використання директиви v-for, щоб відображати список хобі користувача.
◦ Прив’язку стилів для умовного фарбування картки в залежності від віку користувача
(кольори на вподобання студента).
5. Реалізуйте список юзерів:
◦ Розширить список юзерів до 10 включно та виведіть на ui весь список юзерів.
◦ Додайте над списком юзерів toolbar з фільтром у вигляді кнопок (male, female). По
кліку на відповідно кнопку, скривати юзерів в залежності від статі. Якщо список
пустий, вивести напис - 'Список юзерів пустий'
◦ Додайте стилі для картки користувача.
Корисні посилання:
1. https://ua.vuejs.org/guide/introduction.html
2. https://ua.vuejs.org/guide/essentials/template-syntax.html
3. https://ua.vuejs.org/guide/essentials/reactivity-fundamentals.html
4. https://ua.vuejs.org/guide/essentials/class-and-style.html
5. https://ua.vuejs.org/guide/essentials/conditional.html
6. https://ua.vuejs.org/guide/essentials/list.html
7. https://ua.vuejs.org/guide/essentials/component-basics.html
8. https://ua.vuejs.org/guide/extras/composition-api-faq.html
9. https://ua.vuejs.org/guide/extras/composition-api-faq.html
