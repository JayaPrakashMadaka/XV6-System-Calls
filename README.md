## Pre-requisites

```
sudo apt install expect
```


## How to run
Copy the tar ball inside the root directory of xv6

```
tar xzvf check_scripts.tar.gz
./check.sh
```

## Description

User programs:
There are 8 user programs provided to you. First seven (assig1_1.c to assig1_7.c) contains complete code. There is no need to change it. The signatures are as per discussion in the class and the revised assignment statement.

assig1_8.c needs to be modified as per the implementation.

To check, run

```
./check.sh
```

test_assig1.sh will wait for 1 second to get the result and test_assig1_long.sh will wait for 10 seconds. If you want to change this, modify the files and change the sleep value at line 60 and 62 respectively.

## Unicast and Multicast Implementations
![Unicast and Multicast](img/1.png)

