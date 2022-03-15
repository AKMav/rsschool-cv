**Mavrayev Akmal**

*Beginner front-end developer*

## Contacts:

- **My address:** Uzbekistan, Tashkent
- **My phone:** +998901683492
- **E-mail:** [mavrayev@gmail.com](mavrayev@gmail.com)
- **GitHub:** [https://github.com/AKMav](https://github.com/AKMav)
- **Codewars:** [https://www.codewars.com/users/AKMav](https://www.codewars.com/users/AKMav)

## About myself:

I work in a development company as a project manager. I started learning front-end development in 2021.
I like building web-sites, adding interactive elements and writing code. My goal is to be a specialist in web developing.

## Skills:

- HTML5
- CSS3
- JavaScript Basics
- Sublime, VSCode
- Figma, Photoshop
- GitHub, GIT

## Code example:

### Data Reverse

A stream of data is received and needs to be reversed.

Each segment is 8 bits long, meaning the order of these segments needs to be reversed, for example:


```
11111111  00000000  00001111  10101010
 (byte1)   (byte2)   (byte3)   (byte4)
```

should become:

```
10101010  00001111  00000000  11111111
 (byte4)   (byte3)   (byte2)   (byte1)
```
The total number of bits will always be a multiple of 8.

The data is given in an array as such:

```
[1,1,1,1,1,1,1,1,0,0,0,0,0,0,0,0,0,0,0,0,1,1,1,1,1,0,1,0,1,0,1,0]
```
My solution:
```
function dataReverse(data) {
  let result = [];
    while (data.length > 0) {
      result.unshift(...data.splice(0, 8));
  }
  return result;
}
```

## Education:

- Courses on platform **[Hexlet](https://ru.hexlet.io/)**
    - [Introdution to programming](https://ru.hexlet.io/courses/introduction_to_programming)
    - [Basics of programming](https://ru.hexlet.io/courses/programming-basics)
    - [Command line Basics](https://ru.hexlet.io/courses/cli-basics)
- Courses on **[WebReference](https://webref.ru)**
    - HTML lvl 1
    - HTML lvl 2
    - CSS lvl 1
    - CSS lvl 2
- Course on [Stepik](https://stepik.org)
    - JavaScript to begginer - [sertificate](https://stepik.org/cert/1207580)
- Courses ["RS-PreSchool - JavaScript/Front-end. Stage 0"](https://rs.school/js-stage0/);

## Languages:

- Russian
- Uzbek
- English (B1 - Upper Intermediate)
