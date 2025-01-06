# Kata-strophique
# Student's Final Grade [8 kyu] #1

```js
function finalGrade(exam, projects) {
    return ([[(exam > 90 || projects > 10), 100], [(exam > 75 && projects >= 5), 90], [(exam > 50 && projects >= 2), 75]].find((t) => t[0]) || [false, 0])[1];
}
```

# Sentence Smash [8 kyu] #2

```js
function smash (words) {
   return words.join(' ');
};
```

# Growth of a Population [7 kyu] #3

```js
function nbYear(p0, percent, aug, p) {
let firstYear = Math.floor(p0 + p0 * (percent/100) + aug);
let nextP = firstYear;
let nbYear = 1;
while (nextP < p){
  nextP = Math.floor(nextP + nextP * (percent/100) + aug);
  nbYear++;
}
  return nbYear;
}
```

