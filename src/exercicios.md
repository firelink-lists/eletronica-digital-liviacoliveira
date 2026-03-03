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

## Exercício 7

```cpp 
// o resultado do código ainda está dando 0 e 1, não sei o motivo

#include <iostream>
#include <iomanip>

using namespace std;

int main()
{
    const double VALOR_ESPERADO = 1.0; 

    float resultadofloat = 1/3.0 + 1/3.0 + 1/3.0;
    double resultadodouble = 1/3.0 + 1/3.0 + 1/3.0;

    cout << fixed << setprecision(16);

    cout << "Com float: " << resultadofloat << endl;
    cout << "Com double: " << resultadodouble << endl;
    cout << "Erro float: " << VALOR_ESPERADO - resultadofloat << endl;
    cout << "Erro double: " << VALOR_ESPERADO - resultadodouble << endl;

    return 0;
}
´´´