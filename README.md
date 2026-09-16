<!--🚀 Animated Helader -->

<h1 align="center">🚀 ANIL SAIN 1729 | Tech Enthusiast Coding</h1>
 
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&pause=1000&color=00F7FF&center=true&vCenter=true&multiline=true&width=700&height=50&lines=%E2%9C%A8+Innovating+with+Code+%7C+Exploring+AI+%7C+Robotics+%E2%9C%A8" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="400px">
  <br>


</p>

---

|        *Anil nAi*  | 29/02/2004  |
|--------------------|-------------|
| **Location**       | India       |
| **GitHub**         | [Anil nAi](https://github.com/Anil-sain-1279)    |
| **Email**          | asain4773@gmail.com           |
| **Chess**          | [Chess](https://www.chess.com/member/anilsain12)           |
| **Codeforces**     | [Codeforces](https://codeforces.com/profile/anilsain1729)           |
| **CodeChef**       | [CodeChef](https://www.codechef.com/users/anil_sain_1729)           |

---

## 🚀 About Me    
🎓 **CSVTU Bhilai | 2nd Year Student**  



### 🚀 Tech Interests  
🔹 AI & ML 🧠 


## 🛠 Tech Stack


## 🎒 Inventory ##

| Language/Tool      | Logo        | Progress               |       Mastery (%)                                     |
|--------------------|-------------|------------------------|-------------------------------------------------------|
|💻 Programming Languages         |
| **C**              |![C](https://img.shields.io/badge/-C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)| ███████████████░░░░░░  |![C](https://img.shields.io/badge/C-75-blue)|
| **C++**            |![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)| ██████████████░░░░░░░  |![C++](https://img.shields.io/badge/C++-68-blue)|
| **R**              |![R](https://img.shields.io/badge/-R-276DC3?style=for-the-badge&logo=r&logoColor=white)| █████████████░░░░░░░░  |![R](https://img.shields.io/badge/R-57-blue)|
| **Python**         |![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)| ██████████████████░░░  |![Python](https://img.shields.io/badge/PYTHON-90-yellow)|
| **Numpy**          |<img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy"/>| ████████████████░░░░░  |![Numpy](https://img.shields.io/badge/NUMPY-70-indigo)|
| **Pandas**         |<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>| ██████████████░░░░░░░  |![Pandas](https://img.shields.io/badge/PANDAS-65-white)|
| **Matplotlib**     |<img src="https://img.shields.io/badge/Matplotlib-313131?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>| ████████████░░░░░░░░░  |![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-52-pink)|
|🌐 Web Development            |
| **HTML**           |![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)| ████████████░░░░░░░░░  |![HTML](https://img.shields.io/badge/HTML-55-orange)|
| **CSS3**           |![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)| █████░░░░░░░░░░░░░░░░  |![CSS3](https://img.shields.io/badge/CSS3-22-purple)|
| **Javascript**     |![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)| ███░░░░░░░░░░░░░░░░░░  |![JAVASCRIPT](https://img.shields.io/badge/JAVASCRIPT-10-yellow)|

























<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Tic Tac Toe - Anil Sain 1729</title>

<style>

/* =========================
   BASIC
========================= */

* {
    box-sizing: border-box;
}

body {

    margin: 0;

    min-height: 100vh;

    font-family: Arial, sans-serif;

    background:
        linear-gradient(
            135deg,
            #8b5cf6,
            #38bdf8 50%,
            #f472b6
        );

    display: flex;

    justify-content: center;

    align-items: center;

    padding: 20px;

    color: #111d52;

}


/* =========================
   MAIN CONTAINER
========================= */

.app {

    width: min(1100px, 100%);

    background: rgba(255,255,255,0.97);

    border-radius: 30px;

    padding: 30px 45px 35px;

    box-shadow:
        0 20px 60px rgba(20,30,80,0.25);

    text-align: center;

}


/* =========================
   HEADING
========================= */

h1 {

    margin: 0;

    font-size: clamp(45px, 7vw, 70px);

}

h1 span {

    color: #1769e8;

}

h1 b {

    color: #ee3045;

}

.subtitle {

    font-size: 20px;

    margin-top: 5px;

    margin-bottom: 25px;

}


/* =========================
   GAME MODES
========================= */

.modes {

    display: flex;

    gap: 18px;

    margin-bottom: 25px;

}

.modes button {

    flex: 1;

    padding: 17px;

    border: none;

    border-radius: 18px;

    background: #eef2f8;

    color: #18245c;

    font-size: 19px;

    font-weight: bold;

    cursor: pointer;

}

.modes button.active {

    background: #2879ee;

    color: white;

    box-shadow:
        0 8px 22px rgba(40,121,238,0.3);

}


/* =========================
   SETTINGS
========================= */

.settings {

    display: grid;

    grid-template-columns:
        1fr 1.5fr 1fr;

    gap: 20px;

    align-items: center;

    margin-bottom: 25px;

    font-size: 18px;

    font-weight: bold;

}

.settings label {

    display: flex;

    justify-content: center;

    align-items: center;

    gap: 10px;

}

select {

    padding: 10px 15px;

    border: 1px solid #d6deeb;

    border-radius: 12px;

    background: white;

    font-size: 17px;

    font-weight: bold;

}


/* =========================
   STATUS
========================= */

#status {

    padding: 14px;

    border-radius: 15px;

    background: #d7f5df;

    color: #0b8a35;

    font-size: 23px;

    font-weight: bold;

}


/* =========================
   GAME AREA
========================= */

.game-area {

    display: grid;

    grid-template-columns:
        170px 1fr 170px;

    gap: 30px;

    align-items: center;

}


/* =========================
   SCORE CARD
========================= */

.score-card {

    padding: 25px 10px;

    border-radius: 22px;

    background: #eff6ff;

    border: 2px solid #cfe2ff;

}

.score-card.robot {

    background: #fff3f6;

    border-color: #f5cbd5;

}

.icon {

    font-size: 40px;

}

.score-card h2 {

    margin: 8px 0;

}

.score-card p {

    margin: 5px;

}

.score-card strong {

    font-size: 45px;

    color: #1769e8;

}

.robot strong {

    color: #dc2440;

}


/* =========================
   BOARD
========================= */

.board-container {

    display: flex;

    justify-content: center;

}

#board {

    width: min(420px, 70vw);

    height: min(420px, 70vw);

    display: grid;

    grid-template-columns:
        repeat(3, 1fr);

    grid-template-rows:
        repeat(3, 1fr);

    gap: 10px;

    position: relative;

}


/* =========================
   CELLS
========================= */

.cell {

    border: none;

    border-radius: 15px;

    background: #f0f1f3;

    font-size: clamp(55px, 9vw, 90px);

    font-weight: bold;

    cursor: pointer;

    display: flex;

    justify-content: center;

    align-items: center;

    transition: 0.15s;

}

.cell:hover {

    background: #e1e3e6;

    transform: scale(0.98);

}

.cell.x {

    color: #ed3046;

}

.cell.o {

    color: #1879a8;

}


/* =========================
   WINNING LINE
========================= */

#winLine {

    position: absolute;

    height: 9px;

    background: #ee3045;

    border-radius: 20px;

    transform-origin: left center;

    display: none;

    z-index: 5;

    box-shadow:
        0 0 10px rgba(238,48,69,0.4);

}

#winLine.show {

    display: block;

}


/* =========================
   BUTTONS
========================= */

.controls {

    display: flex;

    justify-content: center;

    gap: 20px;

    margin-top: 32px;

}

.controls button {

    border: none;

    border-radius: 15px;

    padding: 15px 28px;

    color: white;

    font-size: 18px;

    font-weight: bold;

    cursor: pointer;

}

#newGame {

    background: #1477f8;

}

#undo {

    background: #8792a4;

}

#resetScore {

    background: #ef3047;

}

.controls button:hover {

    transform: translateY(-2px);

    filter: brightness(0.95);

}


/* =========================
   FOOTER
========================= */

footer {

    margin-top: 28px;

    font-size: 18px;

    font-style: italic;

}


/* =========================
   MOBILE
========================= */

@media(max-width:850px) {

    .app {

        padding: 25px 15px;

    }

    h1 {

        font-size: 45px;

    }

    .game-area {

        grid-template-columns: 1fr;

    }

    .score-card {

        display: none;

    }

    .settings {

        grid-template-columns: 1fr;

    }

    .modes,
    .controls {

        flex-direction: column;

    }

    #board {

        width: 90vw;

        height: 90vw;

        max-width: 390px;

        max-height: 390px;

    }

}

</style>

</head>


<body>


<div class="app">


    <h1>
        <span>Tic</span> Tac <b>Toe</b>
    </h1>


    <p class="subtitle">
        Play with Friend or Challenge the Robot 🤖
    </p>


    <!-- GAME MODE -->

    <div class="modes">

        <button id="humanMode">

            👥 Human vs Human

        </button>


        <button id="robotMode" class="active">

            🤖 Human vs Robot

        </button>

    </div>


    <!-- SETTINGS -->

    <div class="settings">


        <label>

            Your Symbol:

            <select id="symbol">

                <option value="X">
                    X
                </option>

                <option value="O">
                    O
                </option>

            </select>

        </label>


        <div id="status">

            Your Turn

        </div>


        <label id="difficultyBox">

            Difficulty:

            <select id="difficulty">

                <option value="easy">
                    Easy
                </option>

                <option value="medium" selected>
                    Medium
                </option>

                <option value="hard">
                    Hard
                </option>

            </select>

        </label>


    </div>


    <!-- GAME -->

    <div class="game-area">


        <!-- HUMAN SCORE -->

        <div class="score-card you">

            <div class="icon">
                ●
            </div>

            <h2>
                You
            </h2>

            <p>
                Score
            </p>

            <strong id="humanScore">
                0
            </strong>

        </div>


        <!-- BOARD -->

        <div class="board-container">


            <div id="board">


                <button class="cell" data-index="0"></button>

                <button class="cell" data-index="1"></button>

                <button class="cell" data-index="2"></button>


                <button class="cell" data-index="3"></button>

                <button class="cell" data-index="4"></button>

                <button class="cell" data-index="5"></button>


                <button class="cell" data-index="6"></button>

                <button class="cell" data-index="7"></button>

                <button class="cell" data-index="8"></button>


                <!-- WINNING LINE -->

                <div id="winLine"></div>


            </div>


        </div>


        <!-- ROBOT SCORE -->

        <div class="score-card robot">


            <div class="icon">
                🤖
            </div>


            <h2 id="opponent">
                Robot
            </h2>


            <p>
                Score
            </p>


            <strong id="robotScore">
                0
            </strong>


        </div>


    </div>


    <!-- CONTROLS -->

    <div class="controls">


        <button id="newGame">

            ↻ New Game

        </button>


        <button id="undo">

            ↶ Undo

        </button>


        <button id="resetScore">

            ♲ Reset Score

        </button>


    </div>


    <footer>

        "Small games, big thinking!"

    </footer>


</div>


<script>

/* =========================================
   TIC TAC TOE JAVASCRIPT
========================================= */


/* Elements */

const cells =
    [...document.querySelectorAll(".cell")];

const boardElement =
    document.getElementById("board");

const winLine =
    document.getElementById("winLine");

const statusElement =
    document.getElementById("status");

const humanMode =
    document.getElementById("humanMode");

const robotMode =
    document.getElementById("robotMode");

const symbolSelect =
    document.getElementById("symbol");

const difficultySelect =
    document.getElementById("difficulty");

const difficultyBox =
    document.getElementById("difficultyBox");

const opponent =
    document.getElementById("opponent");

const humanScore =
    document.getElementById("humanScore");

const robotScore =
    document.getElementById("robotScore");


/* Winning Patterns */

const winningPatterns = [

    [0, 1, 2],

    [3, 4, 5],

    [6, 7, 8],

    [0, 3, 6],

    [1, 4, 7],

    [2, 5, 8],

    [0, 4, 8],

    [2, 4, 6]

];


/* Game Variables */

let board =
    Array(9).fill("");

let currentPlayer =
    "X";

let gameOver =
    false;

let gameMode =
    "robot";

let human =
    "X";

let robot =
    "O";

let history =
    [];

let scores = {

    human: 0,

    robot: 0

};


/* =========================================
   RENDER BOARD
========================================= */

function renderBoard() {

    cells.forEach(
        (cell, index) => {

            cell.textContent =
                board[index];

            cell.className =
                "cell";


            if (board[index]) {

                cell.classList.add(
                    board[index].toLowerCase()
                );

            }

        }
    );

}


/* =========================================
   CHECK WINNER
========================================= */

function checkWinner(
    testBoard = board
) {

    for (
        let i = 0;
        i < winningPatterns.length;
        i++
    ) {

        const [a, b, c] =
            winningPatterns[i];


        if (

            testBoard[a] !== "" &&

            testBoard[a] === testBoard[b] &&

            testBoard[b] === testBoard[c]

        ) {

            return {

                winner:
                    testBoard[a],

                line:
                    i

            };

        }

    }


    /* Draw */

    if (
        testBoard.every(
            cell => cell !== ""
        )
    ) {

        return {

            winner: "draw",

            line: -1

        };

    }


    return null;

}


/* =========================================
   AVAILABLE CELLS
========================================= */

function getAvailableCells() {

    return board

        .map(
            (value, index) =>
                value === ""
                    ? index
                    : null
        )

        .filter(
            index => index !== null
        );

}


/* =========================================
   MAKE MOVE
========================================= */

function makeMove(
    index,
    player
) {

    if (

        board[index] !== "" ||

        gameOver

    ) {

        return false;

    }


    history.push(
        [...board]
    );


    board[index] =
        player;


    renderBoard();


    return true;

}


/* =========================================
   SHOW WINNING LINE
========================================= */

function showWinningLine(
    lineIndex
) {

    if (lineIndex < 0) {

        return;

    }


    const [
        first,
        ,
        last
    ] =
        winningPatterns[lineIndex];


    const firstCell =
        cells[first]
            .getBoundingClientRect();


    const lastCell =
        cells[last]
            .getBoundingClientRect();


    const boardRect =
        boardElement
            .getBoundingClientRect();


    const x1 =
        firstCell.left +
        firstCell.width / 2 -
        boardRect.left;


    const y1 =
        firstCell.top +
        firstCell.height / 2 -
        boardRect.top;


    const x2 =
        lastCell.left +
        lastCell.width / 2 -
        boardRect.left;


    const y2 =
        lastCell.top +
        lastCell.height / 2 -
        boardRect.top;


    const length =
        Math.hypot(
            x2 - x1,
            y2 - y1
        );


    const angle =
        Math.atan2(
            y2 - y1,
            x2 - x1
        ) *
        180 /
        Math.PI;


    winLine.style.width =
        length + "px";


    winLine.style.left =
        x1 + "px";


    winLine.style.top =
        (y1 - 4) + "px";


    winLine.style.transform =
        `rotate(${angle}deg)`;


    winLine.classList.add(
        "show"
    );

}


/* =========================================
   HIDE WIN LINE
========================================= */

function hideWinningLine() {

    winLine.classList.remove(
        "show"
    );

}


/* =========================================
   UPDATE TURN
========================================= */

function updateTurn() {

    if (
        gameMode === "robot"
    ) {

        if (
            currentPlayer === human
        ) {

            statusElement.textContent =
                "Your Turn";

        } else {

            statusElement.textContent =
                "Robot's Turn";

        }

    }

    else {

        statusElement.textContent =
            `Player ${currentPlayer}'s Turn`;

    }

}


/* =========================================
   FINISH GAME
========================================= */

function finishGame() {

    const result =
        checkWinner();


    /* Continue Game */

    if (!result) {

        currentPlayer =
            currentPlayer === "X"
                ? "O"
                : "X";


        updateTurn();


        return;

    }


    gameOver =
        true;


    /* Draw */

    if (
        result.winner === "draw"
    ) {

        statusElement.textContent =
            "Game Draw!";

        return;

    }


    /* Winning Line */

    showWinningLine(
        result.line
    );


    /* Robot Mode */

    if (
        gameMode === "robot"
    ) {


        if (
            result.winner === human
        ) {

            scores.human++;


            statusElement.textContent =
                "🎉 You Win!";


            statusElement.style.background =
                "#d7f5df";


            statusElement.style.color =
                "#0b8a35";

        }


        else {

            scores.robot++;


            statusElement.textContent =
                "🤖 Robot Wins!";


            statusElement.style.background =
                "#ffe0e5";


            statusElement.style.color =
                "#d51e3b";

        }

    }


    /* Human Mode */

    else {


        if (
            result.winner === human
        ) {

            scores.human++;

        }

        else {

            scores.robot++;

        }


        statusElement.textContent =
            `Player ${result.winner} Wins!`;

    }


    updateScore();

}


/* =========================================
   UPDATE SCORE
========================================= */

function updateScore() {

    humanScore.textContent =
        scores.human;


    robotScore.textContent =
        scores.robot;

}


/* =========================================
   NEW GAME
========================================= */

function newGame() {

    board =
        Array(9).fill("");


    history =
        [];


    gameOver =
        false;


    currentPlayer =
        "X";


    hideWinningLine();


    renderBoard();


    updateTurn();


    /* Robot starts */

    if (

        gameMode === "robot" &&

        human === "O"

    ) {

        setTimeout(
            robotMove,
            400
        );

    }

}


/* =========================================
   RANDOM ROBOT MOVE
========================================= */

function randomMove() {

    const available =
        getAvailableCells();


    return available[
        Math.floor(
            Math.random() *
            available.length
        )
    ];

}


/* =========================================
   FIND WINNING MOVE
========================================= */

function findWinningMove(
    player
) {

    const available =
        getAvailableCells();


    for (
        const index of available
    ) {

        const testBoard =
            [...board];


        testBoard[index] =
            player;


        const result =
            checkWinner(
                testBoard
            );


        if (
            result &&
            result.winner === player
        ) {

            return index;

        }

    }


    return null;

}


/* =========================================
   MINIMAX AI
========================================= */

function minimax(
    testBoard,
    maximizing
) {

    const result =
        checkWinner(
            testBoard
        );


    if (
        result &&
        result.winner === robot
    ) {

        return 10;

    }


    if (
        result &&
        result.winner === human
    ) {

        return -10;

    }


    if (
        result &&
        result.winner === "draw"
    ) {

        return 0;

    }


    const available =
        testBoard

            .map(
                (value, index) =>
                    value === ""
                        ? index
                        : null
            )

            .filter(
                index => index !== null
            );


    /* Robot */

    if (maximizing) {

        let best =
            -Infinity;


        for (
            const index of available
        ) {

            testBoard[index] =
                robot;


            const score =
                minimax(
                    testBoard,
                    false
                );


            testBoard[index] =
                "";


            best =
                Math.max(
                    best,
                    score
                );

        }


        return best;

    }


    /* Human */

    else {

        let best =
            Infinity;


        for (
            const index of available
        ) {

            testBoard[index] =
                human;


            const score =
                minimax(
                    testBoard,
                    true
                );


            testBoard[index] =
                "";


            best =
                Math.min(
                    best,
                    score
                );

        }


        return best;

    }

}


/* =========================================
   HARD ROBOT
========================================= */

function bestRobotMove() {

    const available =
        getAvailableCells();


    let bestScore =
        -Infinity;


    let bestMove =
        available[0];


    for (
        const index of available
    ) {

        board[index] =
            robot;


        const score =
            minimax(
                board,
                false
            );


        board[index] =
            "";


        if (
            score > bestScore
        ) {

            bestScore =
                score;


            bestMove =
                index;

        }

    }


    return bestMove;

}


/* =========================================
   ROBOT MOVE
========================================= */

function robotMove() {

    if (

        gameMode !== "robot" ||

        gameOver ||

        currentPlayer !== robot

    ) {

        return;

    }


    let move;


    const available =
        getAvailableCells();


    /* EASY */

    if (
        difficultySelect.value ===
        "easy"
    ) {

        move =
            randomMove();

    }


    /* MEDIUM */

    else if (
        difficultySelect.value ===
        "medium"
    ) {


        move =
            findWinningMove(
                robot
            );


        /* Block Human */

        if (
            move === null
        ) {

            move =
                findWinningMove(
                    human
                );

        }


        /* Random / Smart */

        if (
            move === null
        ) {

            if (
                Math.random() < 0.5
            ) {

                move =
                    randomMove();

            }

            else {

                move =
                    bestRobotMove();

            }

        }

    }


    /* HARD */

    else {

        move =
            bestRobotMove();

    }


    makeMove(
        move,
        robot
    );


    finishGame();

}


/* =========================================
   CELL CLICK
========================================= */

cells.forEach(
    cell => {

        cell.addEventListener(
            "click",
            () => {


                if (gameOver) {

                    return;

                }


                /* Robot's Turn */

                if (

                    gameMode === "robot" &&

                    currentPlayer !== human

                ) {

                    return;

                }


                const index =
                    Number(
                        cell.dataset.index
                    );


                if (
                    makeMove(
                        index,
                        currentPlayer
                    )
                ) {


                    finishGame();


                    /* Robot Turn */

                    if (

                        gameMode === "robot" &&

                        !gameOver &&

                        currentPlayer === robot

                    ) {

                        setTimeout(
                            robotMove,
                            400
                        );

                    }

                }

            }
        );

    }
);


/* =========================================
   HUMAN VS HUMAN
========================================= */

humanMode.addEventListener(
    "click",
    () => {

        gameMode =
            "human";


        humanMode.classList.add(
            "active"
        );


        robotMode.classList.remove(
            "active"
        );


        difficultyBox.style.visibility =
            "hidden";


        opponent.textContent =
            "Player 2";


        human =
            "X";


        robot =
            "O";


        newGame();

    }
);


/* =========================================
   HUMAN VS ROBOT
========================================= */

robotMode.addEventListener(
    "click",
    () => {

        gameMode =
            "robot";


        robotMode.classList.add(
            "active"
        );


        humanMode.classList.remove(
            "active"
        );


        difficultyBox.style.visibility =
            "visible";


        opponent.textContent =
            "Robot";


        human =
            symbolSelect.value;


        robot =
            human === "X"
                ? "O"
                : "X";


        newGame();

    }
);


/* =========================================
   SYMBOL CHANGE
========================================= */

symbolSelect.addEventListener(
    "change",
    () => {

        human =
            symbolSelect.value;


        robot =
            human === "X"
                ? "O"
                : "X";


        newGame();

    }
);


/* =========================================
   NEW GAME BUTTON
========================================= */

document
    .getElementById("newGame")
    .addEventListener(
        "click",
        newGame
    );


/* =========================================
   UNDO BUTTON
========================================= */

document
    .getElementById("undo")
    .addEventListener(
        "click",
        () => {


            if (

                history.length === 0 ||

                gameOver

            ) {

                return;

            }


            board =
                history.pop();


            /* Robot Game */

            if (

                gameMode === "robot" &&

                history.length > 0

            ) {

                board =
                    history.pop();

            }


            gameOver =
                false;


            hideWinningLine();


            renderBoard();


            currentPlayer =
                gameMode === "robot"
                    ? human
                    : "X";


            updateTurn();

        }
    );


/* =========================================
   RESET SCORE
========================================= */

document
    .getElementById("resetScore")
    .addEventListener(
        "click",
        () => {


            scores = {

                human: 0,

                robot: 0

            };


            updateScore();


            newGame();

        }
    );


/* =========================================
   WINDOW RESIZE
========================================= */

window.addEventListener(
    "resize",
    () => {

        const result =
            checkWinner();


        if (

            result &&

            result.winner !== "draw" &&

            gameOver

        ) {

            showWinningLine(
                result.line
            );

        }

    }
);


/* =========================================
   START GAME
========================================= */

updateScore();

newGame();

</script>

</body>
</html>













































































### 📊 My GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Anil-sain-1729&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Anil Sain GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anil-sain-17297&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
  <br>
  <img src="https://streak-stats.demolab.com?user=Anil-sain-1729&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<br>




