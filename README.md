```jsx
import React from 'react';

function HomePage() {
  return (
    <div>
      <h1>Welcome to the Home Page!</h1>
      <p>This is a simple home page created with React.</p>
      <nav>
        <ul>
          <li>
            <a href="/about">About</a>
          </li>
          <li>
            <a href="/contact">Contact</a>
          </li>
        </ul>
      </nav>
      <section>
        <h2>Featured Content</h2>
        <p>Check out our latest articles and resources.</p>
        {/* Add featured content here */}
      </section>
      <footer>
        <p>&copy; 2023 My Website</p>
      </footer>
    </div>
  );
}

export default HomePage;
```