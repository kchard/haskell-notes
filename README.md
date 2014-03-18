haskell-notes
=============

Resource links and notes related to Haskell

http://www.haskell.org/haskellwiki/How_to_write_a_Haskell_program

http://www.haskell.org/haskellwiki/Structure_of_a_Haskell_project

http://en.wikibooks.org/wiki/Haskell/The_Functor_class

http://en.wikibooks.org/wiki/Haskell/Understanding_monads

https://www.fpcomplete.com/user/pbv/an-introduction-to-quickcheck-testing

http://learnyouahaskell.com/chapters

http://tim.dysinger.net/posts/2014-02-18-haskell-with-emacs.html

http://homepages.inf.ed.ac.uk/wadler/topics/monads.html

http://yannesposito.com/Scratch/en/blog/Yesod-tutorial-for-newbies/

http://www.yesodweb.com/book

https://github.com/bitc/hdevtools

http://bob.ippoli.to/archives/2013/01/11/getting-started-with-haskell/

http://www.stephendiehl.com/posts/vim_haskell.html

https://www.fpcomplete.com/school/starting-with-haskell/libraries-and-frameworks/text-manipulation/json


## Quickstart

```
# mkdir foo && cd foo
# cabal sandbox init
# cabal init
# echo 'main = putStrLn "Hello World"' > Main.hs
# touch LICENSE
# sed -i 's/-- main-is:/main-is: Main.hs/' foo.cabal
# cabal configure && cabal build && cabal run
```
