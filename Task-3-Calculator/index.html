<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lavender Pro Calculator</title>

<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #e6e6fa, #d8bfd8);
    transition: 0.4s;
}

.dark-mode {
    background: linear-gradient(135deg, #240046, #3c096c);
}

.container {
    display: flex;
    gap: 20px;
}

.calculator {
    background: #f3e8ff;
    padding: 20px;
    border-radius: 20px;
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
    width: 340px;
    transition: 0.4s;
}

.dark-mode .calculator {
    background: #3c096c;
}

.display {
    width: 100%;
    height: 60px;
    border: none;
    border-radius: 12px;
    margin-bottom: 10px;
    font-size: 24px;
    text-align: right;
    padding: 10px;
    background: white;
}

.buttons {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
}

button {
    height: 60px;
    border: none;
    border-radius: 12px;
    font-size: 18px;
    cursor: pointer;
    background: #e0bbff;
    transition: 0.2s;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

button:hover {
    background: #d291ff;
    transform: scale(1.05);
}

button:active {
    transform: scale(0.95);
}

.operator {
    background: #c77dff;
    color: white;
}

.equal {
    background: #9d4edd;
    color: white;
    grid-column: span 2;
}

.clear {
    background: #ff99c8;
    color: white;
}

.theme-toggle {
    margin-bottom: 10px;
    width: 100%;
    background: #b583ff;
    color: white;
}

.history {
    width: 200px;
    background: #f8edff;
    padding: 15px;
    border-radius: 20px;
    overflow-y: auto;
    max-height: 420px;
}

.dark-mode .history {
    background: #5a189a;
    color: white;
}

.history h3 {
    margin-top: 0;
    text-align: center;
}

.history p {
    font-size: 14px;
    border-bottom: 1px solid #ccc;
    padding: 5px 0;
}
</style>
</head>

<body>

<div class="container">

<div class="calculator">
    <button id="themeToggle" class="theme-toggle">🌙 Toggle Theme</button>
    <input type="text" id="display" class="display" disabled>

    <div class="buttons">
        <button class="clear">C</button>
        <button class="backspace">⌫</button>
        <button class="operator">%</button>
        <button class="operator">/</button>

        <button>7</button>
        <button>8</button>
        <button>9</button>
        <button class="operator">*</button>

        <button>4</button>
        <button>5</button>
        <button>6</button>
        <button class="operator">-</button>

        <button>1</button>
        <button>2</button>
        <button>3</button>
        <button class="operator">+</button>

        <button>0</button>
        <button>.</button>
        <button class="operator">√</button>
        <button class="operator">x²</button>

        <button class="equal">=</button>
    </div>
</div>

<div class="history">
    <h3>History</h3>
    <div id="historyList"></div>
</div>

</div>

<script>
let display = document.getElementById("display");
let calcButtons = document.querySelectorAll(".buttons button"); // ONLY calculator buttons
let historyList = document.getElementById("historyList");
let themeToggle = document.getElementById("themeToggle");

let currentInput = "";

// Theme toggle (separate logic)
themeToggle.addEventListener("click", function() {
    document.body.classList.toggle("dark-mode");
});

// Loop ONLY calculator buttons
for (let i = 0; i < calcButtons.length; i++) {
    calcButtons[i].addEventListener("click", function() {

        let value = this.innerText;

        if (value === "C") {
            currentInput = "";
            display.value = "";
        }

        else if (value === "⌫") {
            currentInput = currentInput.slice(0, -1);
            display.value = currentInput;
        }

        else if (value === "=") {
            try {
                let result = eval(currentInput);
                historyList.innerHTML += "<p>" + currentInput + " = " + result + "</p>";
                currentInput = result.toString();
                display.value = currentInput;
            } catch {
                display.value = "Error";
                currentInput = "";
            }
        }

        else if (value === "√") {
            if (currentInput !== "") {
                currentInput = Math.sqrt(parseFloat(currentInput)).toString();
                display.value = currentInput;
            }
        }

        else if (value === "x²") {
            if (currentInput !== "") {
                currentInput = Math.pow(parseFloat(currentInput), 2).toString();
                display.value = currentInput;
            }
        }

        else {
            currentInput += value;
            display.value = currentInput;
        }
    });
}

// Keyboard support
document.addEventListener("keydown", function(event) {

    let key = event.key;

    if (!isNaN(key) || "+-*/.%".includes(key)) {
        currentInput += key;
        display.value = currentInput;
    }

    else if (key === "Enter") {
        try {
            let result = eval(currentInput);
            historyList.innerHTML += "<p>" + currentInput + " = " + result + "</p>";
            currentInput = result.toString();
            display.value = currentInput;
        } catch {
            display.value = "Error";
            currentInput = "";
        }
    }

    else if (key === "Backspace") {
        currentInput = currentInput.slice(0, -1);
        display.value = currentInput;
    }

    else if (key === "Escape") {
        currentInput = "";
        display.value = "";
    }
});
</script>

</body>
</html>
