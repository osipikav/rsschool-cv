#### Andrei Osipik

Frontend Developer

#### Contacts:

- Discord: osipikav#4680
- E-mail: osipik.av@yandex.by
- Tel: +375298009607
- GitHub: osipikav

#### About myself:

The old job is almost not fun, so I'm trying to become a developer.

#### Skills and Proficiency:

- HTML5, CSS
- JavaScript Basics
- Git, GitHub
- VSCode

#### Code example:

```
const personalMovieDB = {
count: 0,
movies: {},
actors: {},
genres: [],
privat: false,
start: function () {
personalMovieDB.count = +prompt("сколько фильмов вы уже посмотрели?", '');
while (personalMovieDB.count == '' || personalMovieDB.count == null || isNaN(personalMovieDB.count)) {
personalMovieDB.count = +prompt("сколько фильмов вы уже посмотрели?", '');
}
},
rememberMyFilms: function () {
for (let i = 0; i < 2; i++) {
const a = prompt('Один из последних просмотренных фильмов?', '');
const b = prompt('На сколько оцените его?', '');
if (a != null && b != null && a != '' && b != '' && a.length < 50) {
personalMovieDB.movies[a] = b;
} else {
alert('некорректные данные');
i--;
}
}
},
```

#### Work experience: Nothing yet…

#### Education and courses:

- front-end developer course (stage 0, stage 1) RSSchool
- JS basics course Udemi
- CSS, HTML basics courses Yandex
- JavaScript https://learn.javascript.ru/

#### Language:

- English A2
- Russian
