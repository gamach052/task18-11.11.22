###  [Task 7kyu](https://www.codewars.com/kata/52fba66badcd10859f00097e/train/java)

Trolls are attacking your comment section!

A common way to deal with this situation is to remove all of the vowels from the trolls' comments, neutralizing the threat.

Your task is to write a function that takes a string and return a new string with all vowels removed.

For example, the string "This website is for losers LOL!" would become "Ths wbst s fr lsrs LL!".



### My solution
```Java
public class Troll {
    public static String disemvowel(String str) {
        return str.replaceAll("[AaEeOoUuIi]","");
    }
}
```

### Fav solution
```Java
public class Troll {
    public static String disemvowel(String Z) {
        return Z.replaceAll("(?i)[aeiou]" , "");
    }
}

```
I like this solution because I like it
