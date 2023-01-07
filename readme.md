# Valgrind

## Step 1

Uninstall valgrind if you already have an old buggy or buggy version

```
brew uninstall valgrind
```

## Step 2

Download the valgrind.rb file with the following command

```
curl https://raw.githubusercontent.com/gabrieldejesus/valgrind-macos/main/valgrind.rb -o valgrind.rb
```

## Step 3

Then run the command in the terminal in the same folder where you downloaded the valgrind.rb file

```
brew install --HEAD -s valgrind.rb
```

brew will install valgrind and to use it just run

```
valgrind ./a.out (or whatever name you gave your executable)
```
