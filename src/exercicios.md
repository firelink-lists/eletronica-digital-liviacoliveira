## Exercício 1

```cpp 
void setup() {
  Serial.begin(9600);
  Serial.println("Olá mundo!");
}

void loop() {
}
```

## Exercício 2

```cpp 
#include <iostream>

using namespace std;

int main()
{
    char nome [100];
    cout << "Digite o seu nome:";
    cin >> nome;
    cout << "Olá, " << nome << "!" << endl;
    return 0;
}
``` 

## Exercício 3

```cpp 
#include <iostream>

using namespace std;

int main()
{
    cout << "*" << endl;
    cout << "**" << endl;
    cout << "***" << endl;
    cout << "****" << endl;
    cout << "*****" << endl;
    return 0;
}
```

## Exercício 4

```cpp 
#include <iostream>

using namespace std;

int main()
{
    int valor;
    cout << "Digite o valor de N:";
    cin >> valor;
    cout << "N + 1 = " << valor + 1 << endl;
    return 0;
}
```

## Exercício 5

```cpp 
#include <iostream>

using namespace std;

int main()
{
    int X;
    int Y;
    cout << "Digite o valor de X: ";
    cin >> X;
    cout << "Digite o valor de Y: ";
    cin >> Y;
    cout << "X: " << Y << endl;
    cout << "Y: " << X << endl;
    return 0;
}
```

## Exercício 6

```cpp 
#include <iostream>

using namespace std;

int main()
{
    cout << "Tamanho dos tipos de variaveis em C++:" << endl;
    cout << "int:    " << sizeof(int)    << " bytes" << endl;
    cout << "float:  " << sizeof(float)  << " bytes" << endl;
    cout << "double: " << sizeof(double) << " bytes" << endl;
    cout << "char:   " << sizeof(char)   << " bytes"  << endl;
    cout << "bool:   " << sizeof(bool)   << " bytes"  << endl;

    return 0;
}
```

