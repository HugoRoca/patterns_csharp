---
__Advertisement :)__

- This tutorial was developed in __[Rider](https://nodeca.github.io/pica/demo/)__
- You can use any code editor, for example __[Visual Studio](https://visualstudio.microsoft.com/es/vs/)__

You will like this project!

---

# Patterns C#
Patterns: tips and tricks

```csharp
/*
12345
12345
12345
12345
12345
*/

string output = String.Empty;  
  
for (int j = 0; j < 5; j++)  
{  
    for (int i = 1; i <= 5; i++)  
    {        
	    output += i;
    }
	output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
11111
22222
33333
44444
55555
*/

string output = String.Empty;  
  
for (int j = 1; j <= 5; j++)  
{  
    for (int i = 1; i <= 5; i++)  
    {
        output += j;
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
*****
*****
*****
*****
*****
*/

string output = String.Empty;  
string character = "*";  
  
for (int j = 1; j <= 5; j++)  
{  
    for (int i = 1; i <= 5; i++)  
    {
        output += character;
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
ABCDE
ABCDE
ABCDE
ABCDE
ABCDE
*/

string output = String.Empty;    
    
for (int j = 1; j <= 5; j++)
{    
	for (int i = 1; i <= 5; i++)    
    {  
        output += (char)(i + 64);  
    }
    
    output += "\n";
}    
    
Console.Write(output);
```

```csharp
/*
54321
54321
54321
54321
54321
*/

string output = String.Empty;  
int input = 10;  
  
for (int i = 0; i < input; i++)  
{    
	for (int j = input; j >= 1; j--)    
    {  
        output += j + " ";  
    }
    output += "\n";  
}    
Console.Write(output);
```

```csharp
/*
1
12
123
1234
12345
*/

string output = String.Empty;  
int input = 10;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = 1; j <= i; j++)  
    {
        output += j;
    }
    output += "\n";
}  

Console.Write(output);
```

```csharp
/*
1
22
333
4444
55555
*/

string output = String.Empty;  
int input = 5;    
    
for (int i = 1; i <= input; i++)  
{    
	for (int j = 1; j <= i; j++)  
    {
        output += i + " ";  
    }
    output += "\n";  
}    
Console.Write(output);
```

```csharp
/*
*
**
***
****
*****
*/

string output = String.Empty;  
string character = "*";  
int input = 5;    
    
for (int i = 1; i <= input; i++)  
{    
	for (int j = 1; j <= i; j++)  
    {
        output += character + " ";  
    }
    output += "\n";  
}    
Console.Write(output);
```

```csharp
/*
A
AB
ABC
ABCD
ABCDE
*/

string output = String.Empty;  
int input = 10;    
    
for (int i = 1; i <= input; i++)  
{    
	for (int j = 1; j <= i; j++)  
    {
        output += (char)(j + 64) + " ";  
    }
    output += "\n";  
}    
Console.Write(output);
```

```csharp
/*
5
54
543
5432
54321
*/

string output = String.Empty;  
int input = 10;    
    
for (int i = input; i >= 1; i--)  
{    
	for (int j = input; j >= i; j--)  
    {
        output += j + " ";  
    }
    output += "\n";  
}    
Console.Write(output);
```

```csharp
/*
1
21
321
4321
54321
*/

string output = String.Empty;  
int input = 5;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = i; j >= 1; j--)  
    {
        output += j + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
12345
1234
123
12
1
*/

string output = String.Empty;  
int input = 5;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = 1; j <= i; j++)  
    {
        output += j + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
12345
2345
345
45
5
*/

string output = String.Empty;  
int input = 5;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = i; j <= input; j++)  
    {
        output += j + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
5
54
543
5432
54321
*/

string output = String.Empty;  
int input = 10;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = input; j >= i; j--)  
    {
        output += j + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
54321
5432
543
54
5
*/

string output = String.Empty;  
int input = 5;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = input; j >= i; j--)  
    {
        output += j + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
54321
4321
321
21
1
*/

string output = String.Empty;  
int input = 5;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = i; j >= 1; j--)  
    {
        output += j + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
A
BA
CBA
DCBA
EDCBA
*/
string output = String.Empty;  
int input = 5;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = 1; j <= i; j++)  
    {
        output += (char)(64 + j) + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
ABCDE
ABCD
ABC
AB
A
*/
string output = String.Empty;  
int input = 10;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = 1; j <= i; j++)  
    {
        output += (char)(64 + j) + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
ABCDE
BCDE
CDE
DE
E
*/
string output = String.Empty;  
int input = 5;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = i; j <= input; j++)  
    {
        output += (char)(64 + j) + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
E
E D
E D C
E D C B
E D C B A
*/
string output = String.Empty;  
int input = 5;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = input; j >= i; j--)  
    {
        output += (char)(64 + j) + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
E D C B A
E D C B
E D C
E D
E
*/
string output = String.Empty;  
int input = 5;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = input; j >= i; j--)  
    {
        output += (char)(64 + j) + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
E D C B A
D C B A
C B A
B A
A
*/
string output = String.Empty;  
int input = 5;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = i; j >= 1; j--)  
    {
        output += (char)(64 + j) + " ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
*
* *
* * *
* * * *
* * * * *
*/
string output = String.Empty;  
string character = "*";  
int input = 5;  
  
for (int i = 0; i < input; i++)  
{  
    for (int j = 0; j <= i; j++)  
    {
        output += $"{character} ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
* * * * *
* * * *
* * *
* *
*
*/
string output = String.Empty;  
string character = "*";  
int input = 5;  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = 1; j <= i; j++)  
    {
        output += $"{character} ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
* * * * *
*       *
*       *
*       *
* * * * *
*/
string output = String.Empty;  
string character = "*";  
int input = 10;  
  
for (int i = 0; i < input; i++)  
{  
    for (int j = 0; j < input; j++)  
    {
        character = (i == 0 || i == (input - 1) ||  
                     j == 0 || j == (input - 1))   
                     ? "*" : " ";  
        output += $"{character} ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
*
**
* *
*  *
*****
*/
string output = String.Empty;  
string character = "*";  
int input = 5;  
  
for (int i = 0; i < input; i++)  
{  
    for (int j = 0; j < input; j++)  
    {
        character = (i == (input - 1) || 
	        j == 0 || j == i) ? "*" : " ";  
        output += $"{character} ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
*/
string output = String.Empty;  
int input = 5;  
int aux = 1;  
  
for (int i = 1; i <= input; i++)  
{  
    for (int j = 1; j <= i; j++)  
    {
        output += $"{aux++} ";  
    }
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
1
1 0
1 0 1
1 0 1 0
1 0 1 0 1
*/
string output = String.Empty;  
int input = 10;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  
{    
	for (int j = 1; j <= i; j++)    
    {  
        output += $"{(j % 2)} ";    
    }
    
    output += "\n";  
}

Console.Write(output);
```

```csharp
/*
1
0 1
0 1 0
1 0 1 0
1 0 1 0 1
*/
string output = String.Empty;  
int input = 5;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  {    
	for (int j = 1; j <= i; j++)    
    {  
        output += $"{(aux++) % 2} ";    
    }  
    output += "\n";  
}    
    
Console.Write(output);
```

```csharp
/*
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
*/
string output = String.Empty;  
int input = 10;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  
{    
	for (int j = 1; j <= i; j++)    
    {  
        output += $"{j} ";    
    }  
    output += "\n";  
}  

Console.Write(output);
```

```csharp
/*
        1
      1 2 
    1 2 3
  1 2 3 4
1 2 3 4 5
*/
string output = String.Empty;  
int input = 8;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  
{  
	// string str = String.Empty;
	
    for (int k = input; k >= i; k--)  
    {
        output += "  ";  
    }

	for (int j = 1; j <= i; j++)    
    {  
        output += $"{j} ";    
        // str += $"{j} ";
    }

	// output += str.PadLeft(input * 2) + "\n";
    
    output += "\n";  
}  
  Console.Write(output);
```

```csharp
/*
    1
   1 2
  1 2 3
 1 2 3 4
1 2 3 4 5
*/
string output = String.Empty;  
int input = 8;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  
{  
    for (int k = input; k >= i; k--)  
    {
        output += " ";  
    }

	for (int j = 1; j <= i; j++)    
    {  
	    // Se invierte el espacio
        output += $" {j}";    
    }  
    
    output += "\n";  
}  
  Console.Write(output);
```

```csharp
/*
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1
*/
string output = String.Empty;  
int input = 5;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  
{  
    for (int j = 1; j <= i; j++)    
    {  
        output += $"{j} ";    
    }  
  
    output += "\n";  
}  
  
for (int i = input; i >= 1; i--)  
{  
    for (int j = 1; j <= i; j++)    
    {  
        output += $"{j} ";    
    }  
  
    output += "\n";  
}  
  Console.Write(output);
```

```csharp
/*
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1
*/
string output = String.Empty;  
int input = 10;  
int aux = 1;    
    
for (int i = 1; i <= input; i++)  
{  
    for (int j = 1; j <= i; j++)    
    {  
        output += $"{j} ";    
    }  
  
    output += "\n";  
}  
  
for (int i = input - 1; i >= 1; i--)  
{  
    for (int j = 1; j <= i; j++)    
    {  
        output += $"{j} ";    
    }  
  
    output += "\n";  
}  
  
Console.Write(output);
```

```csharp
/*
        1 1
      1 2 2 1
    1 2 3 3 2 1
  1 2 3 4 4 3 2 1
1 2 3 4 5 5 4 3 2 1
*/
string output = String.Empty;  
int input = 9;  
    
for (int i = 1; i <= input; i++)  
{    
	string str = String.Empty;  
    
    for (int j = 1; j <= i; j++)      
    {    
		str += $"{j} ";      
    }  
        
    output += str.PadLeft(input * 2);  
  
    for (int j = i; j >= 1; j--)  
    {
        output += $"{j} ";  
    }
    
    output += "\n";  
}  

Console.Write(output);
```

```csharp
/*
        1
      1 2 1
    1 2 3 2 1
  1 2 3 4 3 2 1
1 2 3 4 5 4 3 2 1
*/
string output = String.Empty;
int input = 5;

for (int i = 1; i <= input; i++) {
  string str = String.Empty;

  for (int j = 1; j <= i; j++) {
    str += $"{j} ";
  }

  output += str.PadLeft(input * 2);

  for (int j = i - 1; j >= 1; j--) {
    output += $"{j} ";
  }

  output += "\n";
}

Console.Write(output);
```

```csharp
/*
        1
      1 2 1
    1 2 3 2 1
  1 2 3 4 3 2 1
1 2 3 4 5 4 3 2 1
  1 2 3 4 3 2 1
    1 2 3 2 1
      1 2 1
        1
*/
int input = 9;

for (int i = 1; i <= input; i++) {
  for (int j = 1; j <= input - i; j++)
    Console.Write("  ");
  for (int j = 1; j <= i; j++)
    Console.Write(j + " ");
  for (int j = i - 1; j >= 1; j--)
    Console.Write(j + " ");

  Console.WriteLine();
}

for (int i = input - 1; i >= 1; i--) {
  for (int j = 1; j <= input - i; j++)
    Console.Write("  ");

  for (int j = 1; j <= i; j++)
    Console.Write(j + " ");

  for (int j = i - 1; j >= 1; j--)
    Console.Write(j + " ");

  Console.WriteLine();
}
```

```csharp
/*
          0
        1 0 1
      2 1 0 2 1
    3 2 1 0 1 2 3
  4 3 2 1 0 1 2 3 4
5 4 3 2 1 0 1 2 3 4 5
*/
int input = 6;

for (int i = 0; i < input; i++) {
  for (int j = 0; j < input - i; j++)
    Console.Write("  ");

  for (int j = i; j > 0; j--)
    Console.Write("{0} ", j);

  for (int j = 0; j <= i; j++)
    Console.Write("{0} ", j);

  Console.WriteLine();
}
```

```csharp
/*
A B C D E F G G F E D C B A
  A B C D E F F E D C B A
    A B C D E E D C B A
      A B C D D C B A
        A B C C B A
          A B B A
            A A
*/
int input = 9;

for (int i = input; i >= 1; i--) {
  for (int k = 1; k <= input - i; k++)
    Console.Write("  ");

  for (int j = 1; j <= i; j++)
    Console.Write("{0} ", (char)(j + 64));

  for (int j = i; j >= 1; j--)
    Console.Write("{0} ", (char)(j + 64));

  Console.WriteLine();
}
```

```csharp
/*
5 5 5 5 5
4 5 5 5 5
3 4 5 5 5
2 3 4 5 5
1 2 3 4 5
*/
int input = 9;

for (int i = input; i >= 1; i--) {
  for (int j = i; j <= input; j++)
    Console.Write($"{j} ");

  for (int j = 1; j <= i; j++)
    Console.Write($"{input} ");

  Console.WriteLine();
}
```

```csharp
/*
5 4 3 2 *
5 4 3 * 1
5 4 * 2 1
5 * 3 2 1
* 4 3 2 1
*/
int input = 8;

for (int i = 1; i <= input; i++) {
  for (int j = input; j > i; j--)
    Console.Write($"{j} ");

  Console.Write("* ");

  for (int j = i - 1; j >= 1; j--)
    Console.Write($"{j} ");

  Console.WriteLine();
}
```

```csharp
/*
1 2 3 4
2 3 4 1
3 4 1 2
4 1 2 3
*/
int input = 9;

for (int i = 1; i <= input; i++) {
  for (int j = i; j <= input; j++)
    Console.Write($"{j} ");

  for (int j = 1; j <= i - 1; j++)
    Console.Write($"{j} ");

  Console.WriteLine();
}
```

```csharp
/*
4 4 4 4 4 4 4
4 3 3 3 3 3 4
4 3 2 2 2 3 4
4 3 2 1 2 3 4
4 3 2 2 2 3 4
4 3 3 3 3 3 4
4 4 4 4 4 4 4

La variable distancia se calcula para determinar la distancia desde la posición actual hasta el borde del cuadro. La idea es que los valores dismunuyan desde el centro del cuadro hacia los bordes.
*/
int input = 5;
int box = (input * 2) - 1;

for (int i = 1; i <= box; i++) // rows
{
  for (int j = 1; j <= box; j++) // columns
  {
	// Min entre 2 posiciones
    int distance = Math.Min(
      Math.Min(i - 1, box - i),
      Math.Min(j - 1, box - j)
    );
    int value = input - distance;
    Console.Write($"{value} ");
  }

  Console.WriteLine();
}
```

```csharp
/*
* * * * * * * * * * * * * * *
* * * * * * *     * * * * * * *
* * * * * *         * * * * * *
* * * * *             * * * * *
* * * *                 * * * * 
* * *                     * * *
* *                         * *
*                             *
*                             *
* *                         * *
* * *                     * * *
* * * *                 * * * *
* * * * *             * * * * *
* * * * * *         * * * * * *
* * * * * * *     * * * * * * *
* * * * * * * * * * * * * * * *
*/
int input = 8;

for (int i = 1; i <= input; i++) {
  for (int j = i; j <= input; j++)
    Console.Write("* ");

  for (int j = 1; j <= i - 1; j++)
    Console.Write("    ");

  for (int j = input; j >= i; j--)
    Console.Write("* ");

  Console.WriteLine();
}

for (int i = 1; i <= input; i++) {
  for (int j = 1; j <= i; j++)
    Console.Write("* ");

  for (int j = i; j <= input - 1; j++)
    Console.Write("    ");

  for (int j = 1; j <= i; j++)
    Console.Write("* ");

  Console.WriteLine();
}
```

```csharp
/*
*         *        
* *       * *
* * *     * * *
* * * *   * * * *
* * * * * * * * * *
* * * * * * * * * *
* * * *   * * * *
* * *     * * *
* *       * *
*         *
*/
int input = 5;

for (int i = 0; i < input; i++) {
  for (int j = 0; j <= i; j++)
    Console.Write("*  ");

  for (int j = i; j < input - 1; j++)
    Console.Write("   ");

  for (int j = 0; j <= i; j++)
    Console.Write("*  ");

  Console.WriteLine();
}

for (int i = input; i > 0; i--) {
  for (int j = 0; j < i; j++)
    Console.Write("*  ");

  for (int j = input; j > i; j--)
    Console.Write("   ");

  for (int j = 0; j < i; j++)
    Console.Write("*  ");

  Console.WriteLine();
}
```

```csharp
/*
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
11 12 13 14 15
7 8 9 10
4 5 6
2 3
1
*/
int input = 5;
int aux = 1;

for (int i = 1; i <= input; i++) {
  for (int j = 1; j <= i; j++)
    Console.Write($"{aux++} ");

  Console.WriteLine();
}

for (int i = input; i >= 1; i--) {
  for (int j = i; j >= 1; j--)
    Console.Write($"{aux - j} ");

  aux -= i;

  Console.WriteLine();
}
```

```csharp
/*
1
2 4
5 7 9
10 12 14 16
17 19 21 23 25
*/
int input = 5;
int aux = 0;

Console.WriteLine("1 ");

for (int i = 2; i <= input; i++) {
  if ((i % 2 == 0 && aux % 2 != 0) || (i % 2 != 0 && aux % 2 == 0))
    aux--;

  for (int j = 1; j <= i; j++)
    Console.Write($"{aux += 2} ");

  Console.WriteLine();
}
```

```csharp
/*
1 2 3 4
8 7 6 5
9 10 11 12
16 15 14 13
17 18 19 20
24 23 22 21
*/
int rows = 10;
int col = 4, storage = 0;
int aux = 1;

for (int i = 1; i <= rows; i++) {
  if (i % 2 == 0) aux = storage + 4;
  else if (i > 1) {
    aux++;
  }

  for (int j = 1; j <= col; j++) {
    int val = i % 2 == 0 ? aux-- : aux++;

    Console.Write($"{val} ");
    storage++;
  }

  aux = storage;

  Console.WriteLine();
}
```
