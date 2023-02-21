# Daniil Yunin
## Contact

* **Address**: Nizhny Novgorod, Russia
* **Email**: DaniilUnin2002@yandex.ru
* **GitHub**: [DDYunin](https://github.com/DDYunin)
* **Telegram**: [Daniil Yunin](https://t.me/DDYunin)

## About Me
I am 20 years old, I am a student of UNN. I am learning to be a software engineer.
I have some experience working on a study project in a team with subsequent performance in the competition of projects.
In addition to the basic theoretical knowledge obtained at the university, I really want to master the practical skills of developing.
To achieve this goal, I chose the profession as a frontend developer. I am ready to spend much time and desire for this.

> Learn, learn and once again, learn!
> The great aim of education is not knowledge but action.

## Skills

* HTML
* CSS (SASS/SCSS, BEM)
* JavaScript (basic)
* Git/GitHub
* Figma (for web development)
* C/C++ (basic), Python (basic), C# (basic)
* Editors: VSCode, VS

## Code Example

```javascript
function descendingOrder(n){
    let array = []
    let nCopy = n
    while (nCopy >= 0) {
        let digit = nCopy % 10
        array.push(digit)
        nCopy = Math.floor(nCopy / 10)
        if (nCopy === 0) {
            break
        }
    }
    array.sort( (a,b) => (a < b)? 1 : -1)
    return Number(array.join(''));
}
```
