# Budget Allocation Application

## Overview
This project is a Budget Allocation Application built using React, JavaScript, and CSS. The app is designed to plan budgeting expenses for various departments. It includes features such as budget validation, editable budget fields, currency dropdown, and stylized increase/decrease buttons.

## Features
- Budget allocation validation:
  - Accepts only numbers in the allocation field.
  - Ensures the number does not exceed the remaining budget.
- Editable budget value:
  - Allows increasing and decreasing value by 10.
  - Does not allow amount lower than amount spent so far.
  - The upper limit is set to 20,000.
- Currency dropdown:
  - Editable dropdown list with four values ($, 室, ⯬, ॥).
  - Stylized dropdown list with currency change events affecting the entire application.
- Currency prefix added to Change Allocation and budget value textboxes.
- Decrease and Increase buttons for all departments in the allocation.

## Technologies Used
- **React**: For front-end user interface
- **JavaScript**: For dynamic functionality and validation
- **CSS**: For responsive and stylized UI components

## Installation

### Prerequisites
- Node.js and npm installed on your machine

### Steps
1. **Clone the Repository**
    ```sh
    git clone https://github.com/nishchintmakode/budget-allocation-app.git
    cd budget-allocation-app
    ```

2. **Install Dependencies**
    ```sh
    npm install
    ```

3. **Running the Application**
    ```sh
    npm start
    ```

## Usage
- Navigate to `http://localhost:3000` in your browser to use the application.
- Add, edit, or delete budget allocations as needed.
- Use the currency dropdown to change the currency format across the application.
- Increase or decrease budget values using the provided buttons.

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please contact [nishchintsmakode@gmail.com](mailto:nishchintsmakode@gmail.com).
