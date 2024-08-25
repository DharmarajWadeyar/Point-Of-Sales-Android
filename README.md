# Point-Of-Sales-Android

## Project Description
The Point Of Sales Android Application is a user-friendly android app that helps shopkeepers keep track of their products and stocks. The app focuses on the main feature of letting the user input their product details, stock details, and prices to calculate the amount effectively. It also contains categories which are the parts of products, and both categories and products have CRUD operations.

## How to Install and Run the Project

### Software Requirements
- Operating System: Android 5 Lollipop or higher
- Android Studio Software (for emulator setup)
- Java Programming Language

### Hardware Requirements
- Memory: Minimum 1 GB RAM
- Storage: Minimum 5 MB

### Installation Steps
1. Download and install Android Studio from the official website (for emulator setup).
2. Download the project files from the provided Google Drive links:
[Project Document](https://drive.google.com/drive/folders/10TFo77H5z88so8d_WAeZsj-a1QjUjMSK?usp=sharing) & [Project Application](https://drive.google.com/drive/folders/1kXdcwtx5yOPs-9OZuVUovDhsbWOdApcX?usp=sharing)
4. Extract the downloaded files to your local machine.
5. Open Android Studio and set up an Android emulator.
6. Install the app on the emulator or your Android device.
7. Open the app to check and use its features.

## How to Use the Project
1. **Login and Signup**: When the user opens the app, they will see an interface containing Login and Signup options. If the user is already registered, they need to log in. In Signup, the user details such as Name, Username, Password, and Confirm Password will be asked. After successfully signing up, the user needs to log in by entering their username and password.
2. **Dashboard**: Once logged in, the user will see a dashboard containing several modules such as Product, Product View, Category, Category View, POS, and Logout Button.
3. **Product Module**: The user can add products in the Product Module and can edit products in Product View by performing CRUD operations (Edit and Delete).
4. **Category Module**: The Category Module contains the ID and Name of Categories, and Category View contains a list of categories added to it. The user can perform CRUD operations (Edit and Delete) on categories.
5. **POS Module**: The POS Module contains a Product ID Search Bar which displays Product Name, Quantity, and Price, which are editable. This module displays the final amount of products.

## Tests

### Test Case Design
| Sr. No. | Action | Input | Expected Output | Actual Output | Test Result | Test Comment |
|---------|--------|-------|-----------------|---------------|-------------|--------------|
| 1       | Application Launch | Click on App icon | Login page | Login page | Pass | Successful |
| 2       | Enter correct username and password | Username: RAJU, Password: **** | Main Dashboard | Dashboard page | Pass | Dashboard page will display |
| 3       | If username and password are incorrect | Username: RAJU1, Password: ***** | "error: username or password is incorrect" | "error: username or password is incorrect" | Fail | Invalid username and password |
| 4       | If username and password are not entered | Username & password – blank fields | "error: empty fields" | "error: empty fields" | Fail | Unsuccessful |
| 5       | If signup is not entered | Name, username, and password – blank fields | "error: some fields are empty" | "error: some fields are empty" | Fail | Unsuccessful |
| 6       | If signup username and password entered | Username & password | "dashboard" | "dashboard" | Pass | Successful |

## References
We express our sincere gratitude to all those people who helped us in gathering the information while preparing this project. To prepare this project we required information regarding how to develop efficient & proper software on library management system.

Reference Website:
1. https://www.google.com
2. https://www.youtube.com
3. https://www.stack.com

## Credits
I am glad to present my project Point Of Sales Android application. For everything I have achieved, the credit goes to all those who offered me invaluable assistance and guidance to make the project.

- I take this opportunity to express my soulful gratitude to the management of B. N. BANDODKAR COLLEGE OF SCIENCE for giving this opportunity to accomplish this project work.
- I am thankful to our project guide Mr. Abhishek Vartak for his most sincere, useful, and encouraging contribution throughout the project span. Without his support, we couldn’t complete the project on time.
- I am highly obliged to the teaching members of the Computer Science department who took efforts to make the project a successful endeavor. I would also like to thank non-teaching staff members.
- Last, I extend my sincere thanks and appreciation to my family for supporting me a lot in finalizing this project within the limited time frame.

## Contribution
Any contributions to this project are welcome. If you have any issues or requests, feel free to do a pull request. Your contributions are appreciated!

We welcome contributions to this project! Here are the steps to contribute:

1. **Fork the repository**: Click the "Fork" button at the top right of this page to create a copy of the repository on your GitHub account.
2. **Clone the repository**: Use `git clone <your-forked-repository-url>` to clone the repository to your local machine.
3. **Create a new branch**: Use `git checkout -b <branch-name>` to create a new branch for your changes.
4. **Make your changes**: Make the necessary changes to the codebase.
5. **Commit your changes**: Use `git commit -m "Description of your changes"` to commit your changes.
6. **Push to the branch**: Use `git push origin <branch-name>` to push your changes to your forked repository.
7. **Submit a pull request**: Go to the original repository on GitHub and click the "New Pull Request" button to submit your changes for review.

## Contact
For any issues, requests, or contributions, feel free to pull a request or contact me at:
- Email: dharmarajwadeyar@gmail.com
- Phone: +91 8928350830

## License
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
