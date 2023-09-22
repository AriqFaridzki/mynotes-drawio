# Functinal Programming


### Declarative Languagge
FP masuk dalam kategori ini yang artinya dalam paradigma (sistem) ini bagaimana 
kode kita itu dijabarkan **apa yang mau kita capai** tanpa menjelaskan **control flow (prosesnya)**

>  for the same input arguments, the program produces the same result. The order of execution of statements is not important in the declarative programming paradigm. - [scaler.com](https://www.scaler.com/topics/java/functional-programming-in-java/)

contoh

```java
import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
        int[] array = new int[] {1, 2, 3, 4, 5};

        int[] evenArray  = Arrays.stream(array)
                .filter(a -> a % 2 == 0)
                .toArray();

        System.out.println(Arrays.toString(evenArray));
    }
}
```

### Perbedaaan Functional Programming & Purely Functional Programming  
{1}
{2}
{3}
{4}
{5}


(a,b) => {
a + b
}