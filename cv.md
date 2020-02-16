# Aleksandr Zakharov

## Contacts
* Phone: +37525 626 58 76
* Email: Zakharov.faur@gmail.com
* Skype: faurzakharov
* Github: https://github.com/ZakharovOwl
## Summary
I am a purposeful and highly motivated person who can absorb new information quickly. My qualities such as responsibility and flexibility make me good at teamwork. I am highly organized and detail-oriented which I believe is a key to successfully developing.
I want to become a qualified JavaScript Developer.  I'm really interested in this area. And I am ready to do a lot to achieve results. In the future I will build a good career and assemble my best team.
## Skills
* CSS3
* HTML5
* JavaScript
* Git
* Adobe Photoshop
* Graphic design
## portfolio (Nothing)

```javascript
const getFirstNumber = () => Promise.resolve(2);
const getSecondNumber = () => Promise.resolve(2);

const getSumPromise = () => {
  const firstNumberPromise = getFirstNumber();

  return new Promise(resolve => {
    firstNumberPromise
      .then(firstNumber => {
        const secondNumberPromise = getSecondNumber();

        secondNumberPromise
          .then(secondNumber => {
            resolve(firstNumber + secondNumber);
          })
      })
  })
}
getSumPromise().then(sum => console.log(sum));
```

```javascript
const getRandomValue = () => Math.floor(Math.random() * 10);

const func = (callback, value) => {
  setTimeout(() => {
    const newValue = value + 1;
    callback(null, newValue)
  });
}

const asyncFunc = (callback) => {
  setTimeout(() => {
    const value = getRandomValue();
    if (value > 5) {
      return callback('some error')
    }
    return callback(null, value);
  });
}

const callbackFunc = (reject, resolve) => {
  if (reject) {
    console.log(reject);
  } else {
    func(((reject1, resolve1) => {
      console.log(resolve1);
    }), resolve)
  }

  console.log(2);
  console.log(3);
}
asyncFunc(callbackFunc);
```

## Experience (Nothing :cry:)

## Education 
Courses:
* Myfreedom
* Belhard 
* Htmlacademy
* Codeacademy
* The Rolling Scopes School

High Education: 
* BSU, Faculty of Law, Economic law

##  English: 
Pre-Intermediate/ Intermediate (A2/B1)
Courses in the house of officers (2015-2017)