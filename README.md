# Code Quality Quiz

Hallo und vielen Dank, dass du dir die Zeit nimmst eine unserer Challenges zu lösen. Es gibt natürlich auch etwas zu gewinnen! Wenn du mitmachst hast du _sehr gute_ Chancen ein Samsung Smartphone zu bekommen. Bitte achte darauf, dass du zu den verschiedenen Fragen neben deiner Antwort auch
immer deinen Gedankengang aufschreibst, damit wir dein Vorgehen besser nachvollziehen können. Viel Spaß und viel Erfolg!

##### Teilnahme

Pull das Repository, schreibe deine Antworten in diese Datei und schicke sie als Email an challenge@x-cellent.com. 

## 1. Kommentare/Benennung von Variablen und Klassen

Du sollst eine Klasse (class User) für Benutzer deiner Software erstellen. Wie würdest du die Variable für die Email des Benutzers anlegen, A oder B? Bitte begründe deine Entscheidung.

### A

```java
//This is the e-mail of a User.
private string userMail;
```

### B

```java
private string mail;
```



## 2. Camel- und Pascalcase

Was fällt dir bei den beiden Klassen auf?

```java
public class Animal {

public int Age;

    public void getolder () {
        Age++; // increment the age
    }
}
```


```java
public class cat extends Animal {

    public void SaySomething () {
        System.out.println("Miau");
    }
}
```



## 3. Refactoring

Du bekommst die Aufgabe eine Klasse in eurem Projekt zu refactoren. Welche Punkte würdest du beachten, wenn es ums refactoren geht?
Was würdest du bei der unten stehenden Methode anpassen? Bitte teile uns deinen Gedankengänge und Lösung mit Text und/oder (Pseudo-)Code mit.

```java

// Remove employee from list if unavaible.
public void remEmp (users list, user u) {
    if (u.isIll = true) {
        if (u.IsIn(list)) {
            list.rem(u);
        }
    }
    if (u.isPregnant = true) {
        if (u.IsIn(list)) {
            list.rem(u);
        }
    }
    if (u.isOnVacation = true) {
        if (u.IsIn(list)) {
            list.rem(u);
        }
    }
}
```


## 4. Lange Konstruktoren

Was ist deine Meinung zu diesem Konstruktor?

```java
public class Student {
  public Student(String firstname, String name, String street, String city, String university, String department) {
    ...
  }
}
```



## 5. Was stört dich an den beiden Methoden?

Wie findest du die zwei Funktionen?

##### Methode A:

```c
float Q_rsqrt( float number )
{
    long i;
    float x2, y;
    const float threehalfs = 1.5F;

    x2 = number * 0.5F;
    y = number;
    i = * ( long * ) &y;
    i = 0x5f3759df - ( i >> 1);
    y = * ( long * ) &i;
    y = y * ( threehalfs - (x2 * y * y) );
    return y;
}
```

##### Methode B:

```java
/*
* This is a function that calculates the lager of two numbers
* ^_^
*/

/*
* This function returns an int ;D
* an int is a number without a decimal!
*/

int max (int a, int b) {

if (a < b)
    return b;
    /*return b if a is less than b */
else if (a > b && b < a) 
    return a;
    /*return a if a is greater than b*/
else
    /*else return 5 because I'm so random yay :D*/
    return 5;
}
/*this is the end of the program! see you guys later XD*/
```


## Für Spezialisten:

## 6. Strings

```java
public String getUserList(List<User> users) {
    String userList = "";
    for (User user : users) {
      userList += users.getName();
    }
    return userList;
}
```
#### Tipp

Ist mit den String-Objekten alles in Ordnung?



## 7. Warum schlägt der assert immer fehl? Welche Implikationen ergeben sich daraus für monetäre Beträge in Sofware?

```java
public void {
  double d = 1.00 - 0.42;
  assert(d == 0.58);
}
```

#### Tipp

Wie schaut ein double hinter dem Komma wirklich aus?




