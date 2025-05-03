# API-INTEGRATION

*COMPANY*: CIDETECH IT SOLUTIONS

*NAME*: RIFQAH SULAIHA . N

*INTERN ID*: CT04DA506

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

This code represents a simple yet functional weather application developed using HTML, CSS, and JavaScript. The code was written and tested in Visual Studio Code (VS Code), a popular source-code editor developed
by Microsoft. VS Code offers a rich development environment with built-in support for debugging, syntax highlighting, extensions, and live preview capabilities that made it convenient for designing and testing 
this weather application in real-time. The Live Server extension in VS Code likely played an important role in previewing the web page instantly in the browser while making updates to the code.

The primary purpose of this code is to fetch and display current weather data based on the city name entered by the user. It makes use of the OpenWeatherMap API, which is a publicly available API that provides 
weather information for cities across the world. The user enters the name of a city into a text input field on the webpage and clicks a button labeled “Get Weather.” When the button is clicked, a JavaScript
function is triggered which sends a request to the OpenWeatherMap API, retrieves weather data in JSON format, and displays it on the web page dynamically. The data displayed includes the name of the city and 
country, the temperature in degrees Celsius, a brief weather description, and the humidity level.

The structure of the webpage is created using HTML. It includes a title for the browser tab, two images for visual appeal, and a styled container to hold the weather information. The layout is centered and
designed to be visually attractive. The HTML structure also includes an input field for the user to type in the city name and a button that calls the JavaScript function when clicked. There is a dedicated section
where the fetched weather details will be displayed once the user submits a valid city name.

The visual styling of the page is managed through embedded CSS. The page uses a unique font, Script MT, and has a vibrant background color. The weather information is displayed in a rounded container with a 
gradient background and shadow effects, giving it a modern and appealing look. Elements such as padding, margins, text alignment, and font sizes are carefully styled to enhance readability and user experience.
The temperature value is displayed using a large font size and a bright color to make it stand out.

JavaScript is used to handle the dynamic functionality of the app. The script defines an asynchronous function that constructs a URL with the API key and user input, then sends a request using the fetch API. If 
the response is successful and valid, the data is passed to another function that builds a string of HTML containing the weather details and injects it into the page. Error handling is included to display 
appropriate messages if the city is not found or if there is a problem fetching data from the API. This helps ensure the application handles user input gracefully and remains informative even when something goes
wrong.

This weather application is particularly useful for students or beginners in web development who want to understand how to use APIs, handle user input, and manipulate the Document Object Model (DOM) dynamically.
It is also a good project to demonstrate in a portfolio, showing the ability to integrate external data sources into a live application. With further development, it can be enhanced by adding features like real-
time updates, automatic location detection using geolocation APIs, weather icons, or styling enhancements using frameworks like Bootstrap or Tailwind CSS. Overall, this project combines key elements of front-end 
development in a clean, interactive, and educational manner.

Output

![Image](https://github.com/user-attachments/assets/4c4dbfe1-34aa-4d9c-83a6-82651370d8aa)

![Image](https://github.com/user-attachments/assets/43698913-0944-4a63-9f71-53be7d3d17f9)
