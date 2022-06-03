## Lab 1

I installed Visual Studio Code, VS Code extensions (Prettier, ESLint, and Github Pull Requests), Node.js, Git, and Postman.

I then practiced using the command line interface: ![cmd practice](/lab-01-folders.png)

I also created my first Node server-side file, seen below.

#### Code Block
```markdown
/*
    CIT 281, Lab 1
    Name: Hunter Sacrey
*/
function square(num) {
    return num*num;
}
console.log('Square operations:')
for (let i = 2; i <= 10; i+=2) {
    console.log(`Square of ${i} is ${square(i)}`);
}
```
These were the results of the following code: ![lab1 results](/lab-01-node.png)
