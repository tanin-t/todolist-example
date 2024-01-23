```
$ node list-todo.js
(1) [x] Todo 1
(2) [ ] Todo 2
(3) [ ] buy oreo
(4) [x] buy milk
(5) [ ] buy fruit

$ node check-todo.js 5
Checking 5

$ node list-todo.js 
(1) [x] Todo 1
(2) [ ] Todo 2
(3) [ ] buy oreo
(4) [x] buy milk
(5) [x] buy fruit

$ node check-todo.js 2
Checking 2

$ node check-todo.js 3
Checking 3

$ node list-todo.js 
(1) [x] Todo 1
(2) [x] Todo 2
(3) [x] buy oreo
(4) [x] buy milk
(5) [x] buy fruit

$ node delete-todo.js 3
Deleting 3

$ node list-todo.js 
(1) [x] Todo 1
(2) [x] Todo 2
(3) [x] buy milk
(4) [x] buy fruit
```