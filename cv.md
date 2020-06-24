# Yuliya Ramanouskaya

### Contact information  
**Tel**: +375295853332  
**Email**: yulbka13@mail.ru  
**Address**: Belarus, Minsk, Gorodetskaya st., 58-315  
### Summary  
I want to change my professional sphere. I worked at bank as economist, but I realized, that this isn't my calling. I became interested in computer  programming at last summer. I decided to learn javascript because it's very common, has syntax that is similar to English language and has wide range of use. And it is very exciting to create something using lines of code. So, I try to explore new material every day. My near-term goal is to complete "Java-script/Front-end" course. Then I hope to find a job at it-company as javascript developer and advance my skills further.  
### Skills  
- html
- css
- sass
- javascript
- typescript
- git  
### Code examples  
    function check(str, bracketsConfig) {
    let brackets = [];
    for (let i = 0; i < bracketsConfig.length; i++) {    //convert two-dimensional array to one-dimensional array
      let arr = bracketsConfig[i];
      for (let j = 0; j < arr.length; j++) {
          brackets.push(arr[j]);
      }      
    }
    let stack = [];  
    for (let i = 0; i < str.length; i++) {
      let brace = str[i];      
      let j = brackets.indexOf(brace);           
      let l = brackets.lastIndexOf(brace);
       
      if ((j >= 0) && (j % 2 == 0)) {
        if (j == l) {  
        stack.push(j);
        } 
        if (j != l) {
            if (j == stack[stack.length - 1]) {
                stack.pop();
            } else {
                stack.push(j);
            }
        }
      }
      if ((j >= 0) && (j % 2 == 1)) {
          let last = stack.pop();
          if (last != j - 1) return false;
      }  
    }
    return stack.length === 0;
    }
### Experience  
Codewars profile <https://www.codewars.com/users/yulbka> with more than 300 completed tasks.

My projects:
- <https://yulbka.github.io/singolo/>
- <https://yulbka.github.io/codejam-virtual-keyboard/>
- <https://yulbka-rs2020q1-english-for-kids.netlify.app/>
- <https://yulbka-rs2020q1-movie-search.netlify.app/>
- <https://yulbka-rs2020q1-fancy-weather.netlify.app/>
- <https://yulbka-rs2020q1-english-puzzle.netlify.app/>
### Education  
- online studying javascript on website <https://learn.javascript.ru/>
- courses "Learn the command line" and "Learn git" <https://www.codecademy.com/profiles/mega9892831161>
- "Java-script/Front-end" course at Rolling Scope School (from 02.2020 to now) <https://rs.school/js/>
### English
According to EPAM online test I have level B2 <https://training.by/UserProfile#!/Main/?lang=ru>. I learned English at school and university. I also usually watch films and serials on English to improve my skills.
