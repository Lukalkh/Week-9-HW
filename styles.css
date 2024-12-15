// Function to display a greeting
function greetUser() {
    const nameInput = document.getElementById("nameInput").value;
    const outputDiv = document.getElementById("output");
  
    if (nameInput) {
      outputDiv.textContent = `Hello, ${nameInput}! Welcome to the playground!`;
    } else {
      outputDiv.textContent = "Please enter your name.";
    }
  }
  
  // Function to change background color
  function changeBackgroundColor(color) {
    const outputDiv = document.getElementById("output");
  
    if (color) {
      document.body.style.backgroundColor = color;
      outputDiv.textContent = `Background color changed to ${color}!`;
    } else {
      outputDiv.textContent = "Please select a color!";
    }
  }
  
  // Event listeners
  document.getElementById("greetButton").addEventListener("click", greetUser);
  
  document.getElementById("changeColorButton").addEventListener("click", () => {
    changeBackgroundColor("lightyellow");
  });
  
  document.getElementById("colorSelector").addEventListener("change", (event) => {
    const selectedColor = event.target.value;
    changeBackgroundColor(selectedColor);
  });
  
