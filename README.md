# Usage
1. Create a vector of animals structs where each element represents an animal and its attributes (including name, day of birth, month of birth, year of birth, color, species).

```c++

// Struct definition

struct animals {
    std::string name;
    int day;
    int month;
    int year;
    std::string color;
    std::string specie;
};

// Example input vector

std::vector<animals> input1 {
	{"Spike", 1, 1, 2020, "white", "dog"},
        {"Sandy", 3, 5, 2018, "blue", "cat"},
        {"Fluffy", 2, 29, 2016, "black", "sheep"},
        {"Garfield", 9, 17, 1998, "orange", "cat"}
};
```
2. Call the function animalIdentification(std::vector<animals> &input) (which is located in the main.cpp file) in int main().

```c++

// Example implementation

int main()
{
    std::vector<animals> input1 {
        {"Spike", 1, 1, 2020, "white", "dog"},
        {"Sandy", 3, 5, 2018, "blue", "cat"},
        {"Fluffy", 2, 29, 2016, "black", "sheep"},
        {"Garfield", 9, 17, 1998, "orange", "cat"}
    };
    std::cout<<animalIdentification(input1)<<std::endl;

    return 0;
}
```
