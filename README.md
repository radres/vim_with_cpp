# vim_with_cpp

Make sure you have ctags installed.

At the root of your cpp projects execute:
```
ctags --c++-kinds=+p --fields=+iaS --extra=+q --language-force=C++ -R
```

Now you should be able to go to definition by using `ctrl+]` and get back from it by `ctrl+t`

[![Analytics](https://ga-beacon.appspot.com/UA-41104803-6/vim_with_cpp/readme)](https://github.com/igrigorik/ga-beacon)
