this code is the following tutorial.  
https://go.dev/doc/tutorial/create-module

you can build and install this package to your local machine.

```shell
cd hello
go build
go install
```

you must add your module install dir to $PATH.

```shell
export PATH=$PATH:/path/to/your/install/directory
```

you can run it.

```shell
hello
# map[Darrin:Great to see you, Darrin! Gladys:Hail, Gladys! Well met! Samantha:Great to see you, Samantha!]
```
