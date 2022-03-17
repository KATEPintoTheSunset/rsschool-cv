# My CV
# Ekaterina Soloveva

# Contacts for communication: 
## Discord: KATEP#3410
## Email: katepgoesintothesunset@gmail.com

# Brief information about me:
## Hi, my name is Ekaterina and I am 21 years old. I graduated college with common dev knowledge. After that, I worked as a hardware support engineer for a year. I want to gain knowledge and work in the field of Front-end developer.

# Skills:
## I have basic knowledge of JavaScript, HTML, CSS.

# Code examples
## 6 kyu Take a Ten Minute Walk

```
const directions = {
  n: 1,
  w: -1,
  s: -1,
  e: 1
}

function isValidWalk(walk) {
  if(walk.length !== 10){
    return false;
  }
  
  let x = 0, y = 0;
  
  walk.forEach(direction => ['n', 's'].includes(direction) ? x += directions[direction] : y += directions[direction]);
  
  return x === y && x === 0;
}
```

# Work experience
## I worked as hardware support engineer.

# Education
## I graduated college with technical focus. I am currently taking the course "JavaScript/Front-end 2022Q1" from RS school.

# English language A2.