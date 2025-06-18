# Installation

```
npm install gsap
```

---

# Code For the page you want to show this

```jsx
import SplitText from './SplitText';
import { Link } from 'react-router-dom';

function Home() {
  return (
    <main className="homepage">
      <section className="intro">
        <SplitText
          text="Hello, I'm Siam Mehraf"
          className="big-bold-text"
          delay={80}
          duration={0.6}
          interval={8000} // <-- re-animate every 8 seconds
          splitType="words, chars"
          from={{ opacity: 0, y: 40 }}
          to={{ opacity: 1, y: 0 }}
          textAlign="center"
        />
      </section>
    </main>
  );
}

export default Home;
```

---

# What I Modified?

- SplitText Doesn't work on mobile screen properly, Fixed
- Breaking word in smaller screen, Fixed
- Animation still works in the same way, but in smaller screen 'a word' takes different line, not just 'a character', Fixed

# Main Credit

[React Bits](https://reactbits.dev/text-animations/split-text)

---
