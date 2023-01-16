Create a static method that takes two parameters: an ArrayList of Strings called list, and a String called targetWord and removes every instance of targetWord from the ArrayList.

    Examples:
      [java, python, java, scala, ruby, clojure, java] , "java"  -> [python, scala, ruby, clojure] 
      [java, java, java, java, clojure, java] , "java"  -> [clojure]
      [scala, ruby, clojure, java] , "scala"  -> [ruby, clojure, java]
      [java, java, java, java, java] , "java"  -> []