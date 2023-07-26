# TextUtils - Word Counter, Character Counter, and Text Manipulation

TextUtils is a ReactJS web application that allows users to analyze and manipulate text in various ways. It provides functionalities such as word counting, character counting, converting text to uppercase and lowercase, removing extra spaces, and more. The application utilizes React hooks for state management and React Router for handling navigation.

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To run the TextUtils application locally on your machine, follow the steps below:

1. Clone the repository to your local machine using:

```bash
git clone <repository-url>
```

2. Change into the project directory:

```bash
cd TextUtils
```

3. Install the required dependencies using:

```bash
npm install
```

4. Start the development server:

```bash
npm start
```

The application should now be running at `http://localhost:3000`.

## Features

- Word counting: The application allows users to input text and instantly get the word count of the entered text.
- Character counting: Users can see the total number of characters in the text input.
- Text manipulation: Users can convert the text to uppercase or lowercase as per their requirements.
- Remove extra spaces: The application can remove any additional spaces present in the text.
- Copy to clipboard: Users can copy the manipulated text to the clipboard for easy sharing and pasting.

## Demo

You can view a live demo of the TextUtils application at [Live Demo](https://example.com).

## Installation

If you want to integrate TextUtils into your own project, you can install it using npm:

```bash
npm install textutils-react
```

## Usage

To use TextUtils in your React application, import the required components as follows:

```javascript
import React from "react";
import TextForm from "textutils-react";
// other imports...

function App() {
  // your code...
  return (
    <>
      <TextForm />
      {/* other components... */}
    </>
  );
}
```

## Technologies Used

- ReactJS
- React Router
- Bootstrap

## Contributing

Contributions to TextUtils are welcome! If you find any issues or want to enhance the application, feel free to submit a pull request.

## License

MIT License-© RohitG0143. All rights reserved.
