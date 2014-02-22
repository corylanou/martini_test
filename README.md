When entering the directory, run:

```
source dev.env
```

This will set up your go path.

Then, cd go the project directory:

```
cd src/supportlocal/martini_test
```

Get your dependencies

```
go get
```

Build it

```
go build
```

Run it

```
./martinin_test
```


Also, I use a tool that Levi wrote called "glitch".  It's a continous test/vet/build.  You can find it here:

(https://github.com/levicook/glitch)[https://github.com/levicook/glitch]
