# Konovalova Elizaveta

## Contacts
**Email**: f-lestern@mail.ru  
**Discord**: eakonovalova  
**LinkedIn**: [Elizaveta Konovalova](https://www.linkedin.com/in/elizaveta-konovalova/)

## Short info
I have been working as a software quality engineer for 5 years.  
My specialization is web projects, and I want to improve my skills.

## Key skills
* JS, TS
* HTML, CSS
* GitHub, GitLab
* software testing
* test automation, CI

## Code examples
>Реализуйте и экспортируйте функцию getMutualFriends(), которая принимает на вход двух пользователей и возвращает массив состоящий из общих друзей этих пользователей.  
[Full task description.](https://github.com/eakonovalova/Hexlet-courses/blob/main/JS%20An%20Introduction%20to%20OOP/Learning%20tasks/getMutualFriends.js)
```
export const getMutualFriends = (user1, user2) => {

    const firstUserFriends = user1.getFriends();
    const secondUserFriends = user2.getFriends();

    return firstUserFriends.filter((friend) =>
        secondUserFriends.some((fr) => fr.id === friend.id)
    );
};
```

* [More examples of my problem solving](https://github.com/eakonovalova/Hexlet-courses)
* [My little project from Hexlet-courses](https://github.com/eakonovalova/frontend-project-lvl1)

## Work experience
QA engineer at [Tinkoff](https://tinkoffgroup.com/) from September 2017.

I worked in three different teams. Currently, I work in the Tinkoff Asia team.  
The product has not passed the mvp stage yet.

I'm responsible for:
* Requirements testing
* Manual testing for UI and API integrations
* Setting up ci and automating checks for the most critical scenarios

## Education
Plekhanov Russian University of Economics - Bachelor.  
Hexlet courses https://ru.hexlet.io/u/eakonovalova

## Languages
* English - B1
* Russian - Native
