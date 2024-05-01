1. element.value is in string. So if you do + between these, it's going to be string concat not integer addition.
2. add "parseInt" to wrap element.value
