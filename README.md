# CSS Animations Showcase

Welcome to the CSS Animations Showcase repository! Here, you'll find a collection of easy-to-implement CSS animations that can bring your web projects to life.

## Table of Contents
1. [Fade In](#fade-in)
2. [Fade In and Out](#fade-in-and-out)
3. [Slide In from the Left](#slide-in-from-the-left)
4. [Slide In from the Right](#slide-in-from-the-right)
5. [Slide In from the Top](#slide-in-from-the-top)
6. [Bounce](#bounce)
7. [Zoom In](#zoom-in)
8. [Rotate](#rotate)
9. [Pulse](#pulse)
10. [Shake](#shake)
11. [More Animations](#more-animations)

## Animations

### Fade In
```css
@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
Fade In and Out
css
 
@keyframes fadeInOut {
  0%, 100% {
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
}
Slide In from the Left
css
 
@keyframes slideInLeft {
  0% {
    transform: translateX(-100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
Slide In from the Right
css
 
@keyframes slideInRight {
  0% {
    transform: translateX(100%);
    opacity: 0;
  }
  100% {
    transform: translateX(0);
    opacity: 1;
  }
}
Slide In from the Top
css
 
@keyframes slideInTop {
  0% {
    transform: translateY(-100%);
    opacity: 0;
  }
  100% {
    transform: translateY(0);
    opacity: 1;
  }
}
Bounce
css
 
@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-30px);
  }
  60% {
    transform: translateY(-15px);
  }
}
Zoom In
css
 
@keyframes zoomIn {
  0% {
    transform: scale(0.5);
    opacity: 0;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}
Rotate
css
 
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
Pulse
css
 
@keyframes pulse {
  0%, 100% {
    transform: scale(1);
    opacity: 1;
  }
  50% {
    transform: scale(1.1);
    opacity: 0.7;
  }
}
Shake
css
 
@keyframes shake {
  0%, 100% {
    transform: translateX(0);
  }
  10%, 30%, 50%, 70%, 90% {
    transform: translateX(-10px);
  }
  20%, 40%, 60%, 80% {
    transform: translateX(10px);
  }
}
More Animations
Stay tuned for more exciting animations! Feel free to contribute by submitting a pull request with your own favorite animations.

How to Use
Copy the desired animation keyframes into your CSS file.
Apply the animation to an element using the animation property, like so:
css
 
.element {
  animation: fadeInOut 2s infinite;
}
Contributing
We welcome contributions! If you have an animation you'd like to add, please fork the repository, add your animation, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Connect
Feel free to connect with me on LinkedIn for more tips and projects!

Happy animating! 🚀


This single README file includes all the animations and instructions for using and contributing t
