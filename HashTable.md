## **Задача 1**

Имплементирайте  следните функции за HashTable, с ключове от тип int, value-та от тип int.

- void add(int key, int value)
- Value* getByKey(int key)
- operator<< - отпечатва всички двойки (key - value)

ЖОКЕРИ:

Проста хеш функция - int hash(int key) { return key % tableSize}

Примерен обект на HashTable + Value обект

struct Value { T value; Value* next; //constructor }

Node { int key; Value value; //constructor }
