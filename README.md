# Package-POC-Shivam Button Component Library

Welcome to the documentation for the package-poc-shivam button component library! This documentation provides information on how to use and customize the Button component in your React projects.

## Installation

### To install the package-poc-shivam button component library, use npm or yarn:

```javascript
npm install package-poc-shivam
//or
yarn add package-poc-shivam
```

## Example to use in code:

```javascript
import React from 'react';
import { Button } from 'package-poc-shivam';

const MyComponent = () => {
    return (
        <div>
            {' '}
            <Button backgroundColor="#3498db" color="#ffffff">
                {' '}
                Click me{' '}
            </Button>{' '}
        </div>
    );
};

export default MyComponent;
```

---

## APi

> The Button component accepts the following props in addition to the standard HTML button attributes:

-   backgroundColor (optional): Specify the background color of the button.
-   color (optional): Specify the text color of the button.

## License

> This button component library is open-source and available under the MIT License. You are free to use and modify it according to your needs.
