vsego's CV
=

This is my CV. It's here mostly for me. There are likely better places for you to get it, like - for example - my email, which is listed in my CV. 😁 Seriously though, you can just get the processed PDF [here](http://vsego.org/vsego-cv-prog.pdf).

For those interested in the actual TeX code, you want [`vsego-cv-prog.tex`](vsego-cv-prog.tex). The other one ([`vsego-cv-ac.tex`](vsego-cv-ac.tex)) hasn't been maintained since I left academia.

Anyone confused by the [`hook-pre-push`](hook-pre-push) file, it is supposed to be used as a hook:
```
ln -s ../../hook-pre-push .git/hooks/pre-push
```
The reason for it to be here is because I wanted it committed in the repo. It won't work for anyone without my SSH keys anyway, but it'll make it easier for me to set it up in the future.
