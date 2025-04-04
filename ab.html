<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Number Tracking Game</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        input, button { margin: 10px; padding: 10px; font-size: 16px; }
        #numbers-list, #missing-display { margin-top: 20px; font-size: 18px; }
    </style>
</head>
<body>
    <h1>Number Tracking Game</h1>
    <input type="text" id="numberInput" placeholder="Enter a number (00-36)">
    <button onclick="addNumber()">Submit</button>
    <div id="numbers-list">Current Numbers: </div>
    <div id="missing-display">Missing: 18</div>

    <script>
        class NumberTrackingGame {
            constructor(maxNumbers = 18) {
                this.maxNumbers = maxNumbers;
                this.numbers = [];
                this.missingCount = maxNumbers;
            }

            enterNumber(num) {
                // If number exists, remove the oldest entry
                const index = this.numbers.indexOf(num);
                if (index !== -1) {
                    this.numbers.splice(index, 1);
                } else if (this.numbers.length >= this.maxNumbers) {
                    // If the list exceeds max, remove the first number
                    this.numbers.shift();
                }
                
                this.numbers.push(num);
                this.updateMissingCount();
                this.displayStatus();
            }

            updateMissingCount() {
                this.missingCount = Math.max(0, this.maxNumbers - this.numbers.length);
            }

            displayStatus() {
                document.getElementById("numbers-list").innerText = "Current Numbers: " + this.numbers.join(", ");
                document.getElementById("missing-display").innerText = "Missing: " + this.missingCount;
            }
        }

        const game = new NumberTrackingGame();

        function addNumber() {
            const inputElement = document.getElementById("numberInput");
            const rawInput = inputElement.value.trim(); // Trim to remove spaces

            if (rawInput === "") return; // Prevent empty submissions

            if (isValidNumber(rawInput)) {
                game.enterNumber(rawInput);
                inputElement.value = "";
            } else {
                alert("Please enter a valid number: '00', 0 to 36.");
            }
        }

        function isValidNumber(num) {
            return num === "00" || (!isNaN(num) && num >= 0 && num <= 36);
        }

        // Submit number on Enter key press
        document.getElementById("numberInput").addEventListener("keydown", function(event) {
            if (event.key === "Enter") {
                addNumber();
            }
        });
    </script>
</body>
</html>
