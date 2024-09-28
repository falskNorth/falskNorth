<h1>Hallo I'm Kaitlan </h1>


<h3> Welcome to my github, have a look around! 👋👋 </h3>


```java 
import googling.how.to.%%%
import stackoverflow
import praying.for.no.errors

public class Main {
    public static void main(String[] args) {
        String player = "Kaitlan";
        String[] skills = { "Java", "Unity", "C++", "C#", "HTML", "CSS", "Javascript", "Python" };

        LocalDate KaitlanLevel = LocalDate.of(2002, 08, 07);

        int ageLevel = calculateAgeLevel(KaitlanLevel);

        System.out.println("Hello world!");
        System.out.println("My name is " + player + " my level is: ");
        System.out.println("Level " + ageLevel + "!");
        System.out.println("◑____________◑");
    }

    public static int calculateAgeLevel(LocalDate birthDate) {
        LocalDate today = LocalDate.now();
        int yearDiff = today.getYear() - birthDate.getYear();
        if (today.getMonthValue() < birthDate.getMonthValue() ||
                (today.getMonthValue() == birthDate.getMonthValue() && today.getDayOfMonth() < birthDate.getDayOfMonth())) {
            yearDiff--;
        }
        return yearDiff;
    }
}
```

<p> 
<a href="https://www.linkedin.com/in/kaitlan-berg-14517b203/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"  alt="linkedin"
 </a>
</p>
