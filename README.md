# Git-harjoituksia

Harjoitellaan branchien käyttöä

## Tehtävien 5-7 lopputulos

```sh
> git log --oneline --graph

*   f946123 Solve merge conflict [7]
|\  
| * 6822bd7 Update index, better printing for inputs [7]
| *   6a1597a Merge branch 'bugikorjaus' [7]
| |\  
| * | dbfb131 Update index, changes at the top [7]
* | | 333ec95 Update index from the same place previous master update [7]
| |/  
|/|   
* | ceeef3b Update index, changes at the bottom [7]
|/  
* 17126c2 Update index [7]
*   a86960d Merge branch 'master' into laskut
|\  
| * 04fe35a Add license [6]
| * 1326609 Update index [5]
| *   e3b4f3a Merge branch 'laskut'
| |\  
| * | cf43063 Update index, add logger [5]
* | | 71666f4 Add readme [6]
| |/  
|/|   
* | 4d98d8e Add erotus [5]
* | 978f57c Add summa [5]
|/  
* 33bdcfb Init
```

**!** _Main branch renamed to `main` before pushing repo to GitHub. Hence, log contains `master`_ **!**
