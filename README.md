🤖 Automation Testing with Selenium

This repository contains automation testing scripts built using Python and Selenium WebDriver. The goal of this project is to simulate real user interactions with web applications such as searching, clicking, navigation, and form handling.

🚀 Features

* Automated browser interaction using Selenium
* Element identification using XPath, CSS selectors, and IDs
* Explicit waits for dynamic content handling
* Navigation between pages and tabs
* Randomized element selection for testing scenarios
* Add-to-cart automation on e-commerce websites

🛠️ Technologies Used

* Python
* Selenium WebDriver
* ChromeDriver

## 📂 Project Structure

Automation-Testing/
│── amazon_bot.py
│── requirements.txt
│── README.md

## ⚙️ Setup Instructions

1. Clone the repository:

   git clone https://github.com/your-username/Automation-Testing.git

2. Install dependencies:

   pip install selenium

3. Download ChromeDriver:

   * Ensure the ChromeDriver version matches your Chrome browser

4. Run the script:

   python amazon_bot.py

🧪 Example Test Flow

* Open Google
* Search for Amazon
* Navigate to Amazon website
* Search for products (e.g., Books)
* Select a random product
* Add the product to cart

⚠️ Limitations

* Websites like Amazon may detect automation and show CAPTCHA
* UI changes can break locators (XPath/CSS)
* Some elements may require advanced handling (iframes, popups)

🔮 Future Enhancements

* Integration with PyTest for structured test cases
* Data-driven testing
* Logging and reporting system
* Headless browser execution  
* CI/CD integration (GitHub Actions)

## 👨‍💻 Author

Shahid M
