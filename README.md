# Coffee Machine

This project simulates a coffee machine that allows users to select and purchase drinks, manage resources, and track finances. It uses object-oriented programming to manage different aspects of the coffee machine.

## Features

- **Menu Options**: Displays available drink options.
- **Resource Management**: Checks if resources are sufficient for making a drink.
- **Payment Handling**: Manages payments and reports the current balance.
- **Reports**: Provides reports on the coffee maker and money machine status.

## Project Structure

- **`menu.py`**: Contains the `Menu` and `MenuItem` classes that define the available drink options.
- **`coffee_maker.py`**: Contains the `CoffeeMaker` class that handles resource management and coffee preparation.
- **`money_machine.py`**: Contains the `MoneyMachine` class that manages payments and financial reporting.
- **`main.py`**: The main script that runs the coffee machine program.

## Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/DanielThuoMuhia/Coffee-Making-Machine
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd YourRepositoryName
    ```

3. **Ensure Dependencies**:
   - This project does not require any external dependencies beyond standard Python libraries.

## Usage

1. **Run the Program**:

    ```bash
    python main.py
    ```

2. **Interact with the Coffee Machine**:
   - **Options**: View available drink options.
   - **Report**: Check the status of resources and finances.
   - **Make a Choice**: Select a drink to purchase. If resources are sufficient and payment is successful, the drink will be made.

3. **Commands**:
   - `off`: Turn off the coffee machine.
   - `report`: View the current status of the coffee machine and financials.

## Example

When running the program, you will be prompted to select a drink from the available options. After selecting a drink, the program will check if there are enough resources and if the payment is successful. If both conditions are met, it will prepare the coffee and update the resources and finances.

## Code Overview

- **`menu.py`**:
  - `Menu`: Class to handle the menu of available drinks.
  - `MenuItem`: Class to represent each drink item.

- **`coffee_maker.py`**:
  - `CoffeeMaker`: Class to manage resources and make coffee.

- **`money_machine.py`**:
  - `MoneyMachine`: Class to handle payments and financial reporting.

- **`main.py`**:
  - The main script that initializes the coffee maker and money machine, and handles user interactions.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or make a pull request. Ensure that your contributions adhere to the project's coding standards.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to [daniel.thuo@students.jkuat.ac.ke](mailto:daniel.thuo@students.jkuat.ac.ke).

Enjoy your coffee!
