# Polina Posdnyakova
## Contacts
- Location: Moscow, Russian
- Phone: +79995193627
- Email: jerniimy@gmail.com
- Github: [jerniimy](https://github.com/jerniimy)
## About me
Now I work as a web designer, and recently I started learning more about HTML, CSS, and JS so that I wouldn't be constrained by site builders. I could never have imagined how much intriguing it would turn out to be, therefore I'd want to make it my full-time profession.
## Skills
- HTML
- CSS
- JavaScript (Beginner)
- Figma
- Photoshop
## Code example
#### Task:
> Simple, given a string of words, return the length of the shortest word(s).
String will never be empty and you do not need to account for different data types.
```
function findShort(s){
  let array = s.split(' ');
  let min = array[0];
  for (const element of array) {
    if (element.length < min.length) {
      min = element;
    }
  }
  return min.length;
}
```
