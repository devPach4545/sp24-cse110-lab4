1. The bug: The program was concatenating the two inputs instead of adding them. It was considering them string objects.
2. I fixed by using parseFloat. So that the input becomes float and it is possible to add them and get a sum instead of just getting two strings.
