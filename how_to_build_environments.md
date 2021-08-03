# Hello

See: https://zenn.dev/hctaw_srp/articles/d6047b7cce7894

jill is very useful. first of all, install jill.sh:

```
wget https://raw.githubusercontent.com/abelsiqueira/jill/master/jill.sh
bash jill.sh -v 1.6.3
```

then, on my computer, `/home/usr/packages/julias/julia-1.6.3` was made.

and then, confirm your PATH in `.bashrc` so that `.local/bin` can be pathed.

symbolic link. 

```
ln -s /home/usr/packages/julias/julia-1.6.3/bin/julia .local/bin/julia
```

continued....