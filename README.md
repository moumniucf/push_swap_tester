# push_swap_tester

### Usage

First, go to the root of your repository, which is where we can find your Makefile and do

```git clone https://github.com/LeoFu9487/push_swap_tester.git```

```cd push_swap_tester```

And then run

```bash basic_test.sh```

to see if you pass the parsing test (ERROR_TEST), identity test, and small stack test (size 3 and 5)

After that, you can run medium and big stack test with this command

```bash loop.sh <stack size> <loop times>```

For example, this is the result of the following command

```bash loop.sh 100 10```

![example](https://user-images.githubusercontent.com/70040774/118051305-0b7fa580-b381-11eb-9568-36b44748b10f.png)


### Debug

To generate and visualize how your program sorts random numbers, run  

```bash debug.sh <stack size>```

this is the result of the following command

```bash debug.sh 10```

![example2](https://user-images.githubusercontent.com/70040774/118052309-cceaea80-b382-11eb-8c9d-39675e9143ba.png)

or

generate and visualize numbers from 0 to n - 1

```bash debug.sh clean <stack size>```

this is the result of the following command

```bash debug.sh clean 10```

![example3](https://user-images.githubusercontent.com/70040774/118052350-daa07000-b382-11eb-95e4-c8715f70cc05.png)

### Result 

OK : Answer Correct

KO : Wrong Answer

TLE : Time Limit Exceeded, please check if there is an infinite loop in your program (or you can edit the variable ```TIME_LIMIT``` in *.sh file)

ERROR : Unknown Instructions

leaks command not found : can't test your memory with command ```leaks```

### Clean

```bash clean.sh```

can remove every test case and output file

### Contact : 

yfu@student.42lyon.fr

or DM me on the slack
