# NextScrollTo NPM Package

NextScrollTo is a lightweight React component designed to enhance user experience by providing a convenient way to scroll back to the top of the page. With automatic detection of scroll position, it displays a customizable button when the user reaches the bottom of the page.

## Installation

Install ScrollToTop via npm:

```bash
npm install next-scroll-to

```

## Usage

Simply import the ScrollToTop component and add it to your React application:

```bash
import * as React from "react";
import { ScrollToTop } from "next-scroll-to";

const App = () => {
  return (
    <div>
      {/* Your content */}
      <ScrollToTop />
    </div>
  );
};

export default App;
```

## Features

- Automatically detects when the user scrolls to the bottom of the page
- Displays a customizable "Scroll to Top" button for easy navigation
- Smooth scrolling animation provides a polished user experience
