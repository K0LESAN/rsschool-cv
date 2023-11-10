# **[rsschool-cv](https://k0lesan.github.io/rsschool-cv/cv)**
***
# **Ilya Kolesnikov**
***
## **Junior Frontend Developer**
***
## **Contact information:**

**Phone:** +7 (995) 600-77-62

**E-mail:** k0lesan2k00@gmail.com
***
## **Briefly About Myself:**

Beginning my career as a layout designer with limited skills at a local newspaper, I gradually honed my proficiency in printing design. My fascination with printing technologies eventually led me to secure a position as a Prepress and DTP Engineer at the largest printing house in my city. There, I continued to self-educate and explore the process of creating various printed materials, including wine and food labels, magazines, and more.

Several years ago, I became passionate about retouching. Through dedicated practice, I mastered various retouching techniques and became skilled in using graphic tablets and Adobe Photoshop. Eventually, I landed my first job as a professional retoucher.

As a remote retoucher, I have found myself with extra free time, which I have invested in learning Frontend Development. I am drawn to this field because of its potential for professional growth, vast resources for self-education, and large community of developers.

I am confident that my ability to learn quickly and acquire new skills will allow me to become a proficient Frontend Developer.
***
## **Skills and Proficiency:**

* HTML5, CSS3 (SASS)
* Javascript
* Git, GitHub
* VS Code
* Figma
***
## **Code example:**

**Disemvowel Trolls KATA from CODEWARS:** *Trolls are attacking your comment section! A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat. Your task is to write a function that takes a string and return a new string with all vowels removed. For example, the string "This website is for losers LOL!" would become "Ths wbst s fr lsrs LL!".*

```
function disemvowel(str) {
  const vowel = ['a', 'e', 'i', 'o', 'u']
  let localStr = str
  
  for(let i = 0; i < str.length; i++) { 
    for(let j = 0; j < vowel.length; j++) {
      if(str[i] !== undefined && str[i].toLowerCase() === vowel[j]) {
        str = str.slice(0, i) + str.slice(i + 1, str.length)
        i--
      }
    }
  }
  
  return str;
}
```
***
## **Courses:**

* HTML and CSS Tutorials on the w3schools (completed)
* JavaScript Manual on learnjavascript.ru (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
***
##**Languages:**

* English
* Russian
