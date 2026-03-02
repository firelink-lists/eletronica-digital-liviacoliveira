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
