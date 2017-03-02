# NCH (or meowcat, or sneakerchat)

To run it:

```bash
# first 1337 is base listening port, second one is the remote clients base port
./nch 1337 1337 `hostname`
```

If you want to run two clients locally, in one terminal:

```bash
# note the extra "1" in the second port num, thats the other client
./nch 1337 11337 `hostname`
```

```bash
# note the reserved port numbers
./nch 11337 1337 `hostname`
```

Now, to connect from one to the other, in the first one type:

```
++host-name-to-connect-to
```

so if you want to connect to a hostname of `sneakercomp.local`, it would be

```
++sneakercomp.local
```

Then just chat away!

