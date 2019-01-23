# color-git-profile
Adiciona cor no GIT
Copie este aquivo `.bash_aliases` de onde você baixou:


 ```
 mv /home/seu-usuario/diretorio-onde-esta-oseu-arquivo/.bash_aliases ~/.bash_aliases
```

Abra o seu `$ nano ~/.bash` è adicione ao final

E adicione o seguinte comando:

``` 
if [ -f ~/.bash_aliases ]; then
    . ~/.bash_aliases
fi

```

Reinicie o Terminal
