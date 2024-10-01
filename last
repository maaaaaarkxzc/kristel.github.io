// Get the button and animation elements
const button = document.querySelector('.button .btn');
const animation = document.querySelector('.animation');

// Add an event listener to the button
button.addEventListener('click', () => {
  // Show the animation
  animation.style.display = 'block';
  
  // Add a fade-in effect to the animation
  animation.classList.add('fadeIn');
  
  // Add a timeout to hide the animation after 3 seconds
  setTimeout(() => {
    animation.style.display = 'none';
  }, 3000);
});

// Add a fade-in effect to the animation
.animation.fadeIn {
  animation: fadeIn 0.5s;
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
