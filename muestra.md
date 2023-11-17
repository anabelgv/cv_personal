# Muestra de Trabajo

## Java

````java
import java.util.Scanner;
public class prog{
public static void main(String[] args) {
    Scanner sc = new Scanner (System.in);
    int numero;
 numero = sc.nextInt();
if (numero >= 0 && numero <= 9) {
            int i = 0;
            while (i <= 10) {
                int resultado = numero * i;
                System.out.println(numero + " x " + i + " = " + resultado);
                i++;
            }
        } else {
            System.out.println("Número no válido");
        }
    }
}
````

## HTML
 ```html
<!DOCTYPE html>

<html>
<head>
<meta charset="UTF-8">
<title>Anabel Gomez Vilas</title>
<link rel="shortcut icon" href="./favicon.ico" type="image/x-icon">
</head>
<body>
    <a name="top">top</a>
    <strong>Bees</strong>
<h1><em>information about bees</em></h1>
<h2>Common Types</h2>
    <u1>
        <li>carpenter bee</li>
        <li>bumble bee</li>
        <li>sweat bee</li>
        <li>western honey bee</li>
    </u1>
    <img src="./img/bee.jpg" alt="bees" width="300">
    <h2>types of bees in a hive</h2>
    <ol>
        <li>Queen</li>
        <li>workers</li>
        <li>drones</li>
    </ol>
    <img src="./img/typesbees.jpg" alt="bees" width="300">
    <a href="./bee.html"></a>
    <h3>reference page</h3>
    <a href="https://www.gardenbetty.com/bees/">Bees reference page</a>
    <h5>Up</h5>
    <a href="#top">top</a>
    
</body>



</html>
```