<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Tic-Tac-Toe</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #FF6B6B 0%, #556270 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: white;
        }
        .container {
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }
        h1 { margin-bottom: 20px; font-weight: 300; letter-spacing: 2px; }
        .board {
            display: grid;
            grid-template-columns: repeat(3, 100px);
            grid-template-rows: repeat(3, 100px);
            gap: 10px;
            margin-bottom: 20px;
        }
        .cell {
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 3rem;
            cursor: pointer;
            transition: background 0.3s, transform 0.2s;
            user-select: none;
        }
        .cell:hover { background: rgba(255, 255, 255, 0.4); }
        .cell:active { transform: scale(0.95); }
        .cell.x { color: #8fd3f4; }
        .cell.o { color: #fecfef; }
        
        .status {
            font-size: 1.2rem;
            margin-bottom: 20px;
            height: 1.5em;
        }
        .btn-reset {
            padding: 10px 30px;
            font-size: 1rem;
            background: white;
            color: #556270;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s;
        }
        .btn-reset:hover {
            background: #f0f0f0;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>TIC TAC TOE</h1>
        <div class="status" id="status">Player X's Turn</div>
        <div class="board" id="board">
            <div class="cell" data-index="0"></div>
            <div class="cell" data-index="1"></div>
            <div class="cell" data-index="2"></div>
            <div class="cell" data-index="3"></div>
            <div class="cell" data-index="4"></div>
            <div class="cell" data-index="5"></div>
            <div class="cell" data-index="6"></div>
            <div class="cell" data-index="7"></div>
            <div class="cell" data-index="8"></div>
        </div>
        <button class="btn-reset" onclick="resetGame()">Restart Game</button>
    </div>

    <script>
        let currentPlayer = 'X';
        let gameState = ["", "", "", "", "", "", "", "", ""];
        let gameActive = true;
        const statusDisplay = document.getElementById('status');

        const winningConditions = [
            [0, 1, 2], [3, 4, 5], [6, 7, 8], // แนวนอน
            [0, 3, 6], [1, 4, 7], [2, 5, 8], // แนวตั้ง
            [0, 4, 8], [2, 4, 6]             // แนวทแยง
        ];

        document.querySelectorAll('.cell').forEach(cell => {
            cell.addEventListener('click', handleCellClick);
        });

        function handleCellClick(e) {
            const clickedCell = e.target;
            const clickedCellIndex = parseInt(clickedCell.getAttribute('data-index'));

            if (gameState[clickedCellIndex] !== "" || !gameActive) {
                return;
            }

            handleCellPlayed(clickedCell, clickedCellIndex);
            handleResultValidation();
        }

        function handleCellPlayed(clickedCell, clickedCellIndex) {
            gameState[clickedCellIndex] = currentPlayer;
            clickedCell.textContent = currentPlayer;
            clickedCell.classList.add(currentPlayer.toLowerCase());
        }

        function handleResultValidation() {
            let roundWon = false;
            for (let i = 0; i <= 7; i++) {
                const winCondition = winningConditions[i];
                let a = gameState[winCondition[0]];
                let b = gameState[winCondition[1]];
                let c = gameState[winCondition[2]];
                if (a === '' || b === '' || c === '') continue;
                if (a === b && b === c) {
                    roundWon = true;
                    break;
                }
            }

            if (roundWon) {
                statusDisplay.textContent = `Player ${currentPlayer} Wins! 🎉`;
                gameActive = false;
                return;
            }

            if (!gameState.includes("")) {
                statusDisplay.textContent = `Draw! 🤝`;
                gameActive = false;
                return;
            }

            currentPlayer = currentPlayer === "X" ? "O" : "X";
            statusDisplay.textContent = `Player ${currentPlayer}'s Turn`;
        }

        function resetGame() {
            gameActive = true;
            currentPlayer = "X";
            gameState = ["", "", "", "", "", "", "", "", ""];
            statusDisplay.textContent = `Player X's Turn`;
            document.querySelectorAll('.cell').forEach(cell => {
                cell.textContent = "";
                cell.classList.remove('x', 'o');
            });
        }
    </script>
</body>
</html>
