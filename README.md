Certainly! Here’s a detailed `README.md` file for your `netflix-loading-indicator` GitHub repository:

```markdown
# Netflix Loading Indicator

A Netflix-style loading indicator for React applications. This component provides a sleek and modern loading spinner that mimics the loading animation seen on Netflix.

## Features

- **Customizable Size and Color**: Easily adjust the size and color of the loading spinner.
- **Lightweight**: Minimalistic design with a small bundle size.
- **Easy Integration**: Simple to add to any React project.

## Installation

To use the `netflix-loading-indicator` package in your React project, follow these steps:

1. **Install the package**:

   ```sh
   npm install netflix-loading-indicator
   ```

   Or, if you are using Yarn:

   ```sh
   yarn add netflix-loading-indicator
   ```

## Usage

To use the `LoadingIndicator` component, import it into your React component and include it in your JSX. Here’s an example of how to use it:

```jsx
import React from 'react';
import LoadingIndicator from 'netflix-loading-indicator';
import './App.css';

function App() {
  return (
    <div className="App">
      <h1>Netflix Loading Indicator</h1>
      <LoadingIndicator size="50px" color="#e50914" />
    </div>
  );
}

export default App;
```

## Props

The `LoadingIndicator` component accepts the following props:

- **`size`** (string): Defines the size of the loading spinner. Example values: `"50px"`, `"100px"`.
- **`color`** (string): Sets the color of the loading spinner. Example values: `"#e50914"`, `"blue"`.

### Example with Custom Props

```jsx
<LoadingIndicator size="80px" color="#00bfff" />
```

## Development

To contribute to the development of this package, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/aaditya7788/netflix-loading-indicator.git
   cd netflix-loading-indicator
   ```

2. **Install dependencies**:

   ```sh
   npm install
   ```

3. **Run the development build**:

   ```sh
   npm run build
   ```

## Testing

Ensure your changes work correctly by running the build script and testing the component in your React application.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please submit a pull request. Ensure your changes are well-documented and tested.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please open an issue on the [GitHub repository](https://github.com/aaditya7788/netflix-loading-indicator) or contact me at [aadityasahani78@gmail.com](mailto:aadityasahani78@gmail.com).

---

Thank you for using `netflix-loading-indicator`! We hope it adds a stylish touch to your React projects.
