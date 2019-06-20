# Crontab

Hi, i want to show you how can we use crontab in linux. It's make a timer for executable file in linux

Sometimes you need run file more than once but you wouldn't always run manually because could be happened busy time for you. 

Here crontab comes into play, just you have to do, add **crontab job** your executable file.

You can check all crontab jobs ;

```sh
crontab -l 
```

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/Screenshot_2.png)

There is a lot of job !

There have a rule when you add job to crontab, you don't need to keep in mind, just check out ```sh cat /etc/crontab```

![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/Screenshot_3.png)

As you see, there is a **Example of job defination** you can get referance this file and try to add new job.

Let's try

- Firs i need a sh script(you don't need special things)

```sh
touch print_date.sh 

date>example.txt

```

```sh
chmod +x print_date.sh

```


```sh
crontab -e

* * * * * /tmp/print_date.sh //that means code run every minute

```
Also this site very helpfull  https://crontab.guru/


![alt text](https://github.com/denizparlak07/Documentation/blob/master/images/crontab_gif.gif)

Peace..
