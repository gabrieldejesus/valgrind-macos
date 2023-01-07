# Valgrind

## Step 1

Install brew

```
rm -rf $HOME/.brew && git clone --depth=1 https://github.com/Homebrew/brew $HOME/.brew && echo 'export PATH=$HOME/.brew/bin:$PATH' >> $HOME/.zshrc && source $HOME/.zshrc && brew update
```

## Step 2

Uninstall valgrind if you already have an old buggy or buggy version

```
brew uninstall valgrind
```

## Step 3

Download the valgrind.rb file with the following command

```
curl https://raw.githubusercontent.com/gabrieldejesus/valgrind-macos/main/valgrind.rb -o valgrind.rb
```

## Step 4

Then run the command in the terminal in the same folder where you downloaded the valgrind.rb file

```
brew install --HEAD -s valgrind.rb
```

---

brew will install valgrind and to use it just run

```
valgrind ./a.out (or whatever name you gave your executable)
```
