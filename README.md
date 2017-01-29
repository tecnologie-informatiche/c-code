# c-code

## Operazioni sui bit

### Operatori a bit

| Operatore   |      Significato      | 
|----------|:-------------:|
| &  |  Operatore a bit AND |
| \| |    Operatore a bit OR   |
| ^ | Operatore a bit OR Esclusivo |

### Example

    #include <iostream>

    int main()
    {
        int num1, num2, result;

        num1 = 0b1101; //13
        num2 = 0xf; //15
        result = num1 ^ num2;
        std::cout<< result << endl; //2

        return 0;
    }


