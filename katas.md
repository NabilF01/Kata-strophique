# Kata-strophique
# Student's Final Grade [8 kyu] #1

```js
function finalGrade(exam, projects) {
    return ([[(exam > 90 || projects > 10), 100], [(exam > 75 && projects >= 5), 90], [(exam > 50 && projects >= 2), 75]].find((t) => t[0]) || [false, 0])[1];
}
```

