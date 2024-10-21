#include <stdio.h>

// Function to convert Celsius to Fahrenheit
float celsiusToFahrenheit(float celsius) {
    return (celsius * 9 / 5) + 32;
}

// Function to convert Celsius to Kelvin
float celsiusToKelvin(float celsius) {
    return celsius + 273.15;
}

// Function to convert Fahrenheit to Celsius
float fahrenheitToCelsius(float fahrenheit) {
    return (fahrenheit - 32) * 5 / 9;
}

// Function to convert Fahrenheit to Kelvin
float fahrenheitToKelvin(float fahrenheit) {
    return fahrenheitToCelsius(fahrenheit) + 273.15;
}

// Function to convert Kelvin to Celsius
float kelvinToCelsius(float kelvin) {
    return kelvin - 273.15;
}

// Function to convert Kelvin to Fahrenheit
float kelvinToFahrenheit(float kelvin) {
    return celsiusToFahrenheit(kelvinToCelsius(kelvin));
}

int main() {
    int choice;
    float temperature, result;

    printf("Temperature Conversion Program\n");
    printf("1. Celsius to Fahrenheit\n");
    printf("2. Celsius to Kelvin\n");
    printf("3. Fahrenheit to Celsius\n");
    printf("4. Fahrenheit to Kelvin\n");
    printf("5. Kelvin to Celsius\n");
    printf("6. Kelvin to Fahrenheit\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    printf("Enter temperature: ");
    scanf("%f", &temperature);

    switch (choice) 
{
        case 1:
            result = celsiusToFahrenheit(temperature);
            printf("%.2f Celsius = %.2f Fahrenheit\n", temperature, result);
            break;
        case 2:
            result = celsiusToKelvin(temperature);
            printf("%.2f Celsius = %.2f Kelvin\n", temperature, result);
            break;
        case 3:
            result = fahrenheitToCelsius(temperature);
            printf("%.2f Fahrenheit = %.2f Celsius\n", temperature, result);
            break;
        case 4:
            result = fahrenheitToKelvin(temperature);
            printf("%.2f Fahrenheit = %.2f Kelvin\n", temperature, result);
            break;
        case 5:
            result = kelvinToCelsius(temperature);
            printf("%.2f Kelvin = %.2f Celsius\n", temperature, result);
            break;
        case 6:
            result = kelvinToFahrenheit(temperature);
            printf("%.2f Kelvin = %.2f Fahrenheit\n", temperature, result);
            break;
        default:
            printf("Invalid choice!\n");
    }

    return 0;
}
