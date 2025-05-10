/*
    <img src="https://supersimple.dev/projects/advanced-functions/images/rock-emoji.png" alt="Rock">
    <img src="https://supersimple.dev/projects/advanced-functions/images/paper-emoji.png" alt="Paper">
    <img src="https://supersimple.dev/projects/advanced-functions/images/scissors-emoji.png" alt="Scissors">
*/

document.querySelectorAll('a[href="#Game"]').forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      document.querySelector('#game').scrollIntoView({ behavior: 'smooth' });
    });
});

let computerChoice, result, autoPlayID;
let autoPlaying = false;
let score = JSON.parse(localStorage.getItem('score'));

if (!score) {
    score = {win: 0, loss: 0, tie: 0};
};

updateScore();

function getComputerChoice() {
    let randomNumber = Math.random();

    if (randomNumber <= 0.3) {
        computerChoice = 'Rock'
        document.getElementById("computer").src = `https://supersimple.dev/projects/advanced-functions/images/rock-emoji.png`;
    }
    else if (randomNumber > 0.3 && randomNumber <= 0.6) {
        computerChoice = 'Paper';
        document.getElementById("computer").src = `https://supersimple.dev/projects/advanced-functions/images/paper-emoji.png`;
    }
    else {
        computerChoice = 'Scissor';
        document.getElementById("computer").src = `https://supersimple.dev/projects/advanced-functions/images/scissors-emoji.png`;
    };

    return computerChoice;
}

function Result(userChoice) {
    getComputerChoice();

    if (userChoice === 'Rock') {
        if (computerChoice === 'Rock') {
            result = 'Tie';
            score.tie++;
        }
        if (computerChoice === 'Paper') {
            result = 'You Lose!'
            score.loss++;
        }
        if (computerChoice === 'Scissor') {
            result = 'You Win!';
            score.win++;
        }
        document.getElementById('user').src = 'https://supersimple.dev/projects/advanced-functions/images/rock-emoji.png';
    }
    if (userChoice === 'Paper') {
        if (computerChoice === 'Rock') {
            result = 'You win!';
            score.win++
        }
        if (computerChoice === 'Paper') {
            result = 'Tie'
            score.tie++
        }
        if (computerChoice === 'Scissor') {
            result = 'You lose!';
            score.loss++
        }
        document.getElementById("user").src = `https://supersimple.dev/projects/advanced-functions/images/paper-emoji.png`;
    }
    if (userChoice === 'Scissor') {
        if (computerChoice === 'Rock') {
            result = 'You lose!';
            score.loss++
        }
        if (computerChoice === 'Paper') {
            result = 'You win!'
            score.win++
        }
        if (computerChoice === 'Scissor') {
            result = 'Tie';
            score.tie++
        }
        document.getElementById("user").src = `https://supersimple.dev/projects/advanced-functions/images/scissors-emoji.png`;
    }

    updateScore();
    document.getElementById('result').innerText = result;
}

function autoPlay() {
    if (!autoPlaying) {
        autoPlayID = setInterval(function() {
            let autoPlayer = getComputerChoice(); 
            Result(autoPlayer);
        }, 1000);
        document.querySelector('.autoPlay').innerText = 'Stop AutoPlay';
        autoPlaying = true;
    }
    else {
        clearInterval(autoPlayID);
        document.querySelector('.autoPlay').innerText = 'AutoPlay';
        autoPlaying = false;
    }
}

function playWithComputer() {
    if (autoPlaying) {
        clearInterval(autoPlayID);
        document.querySelector('.autoPlay').innerText = 'AutoPlay';
        autoPlaying = false;
    }
}

function updateScore() {
    document.querySelector('.win').innerText = score.win;
    document.querySelector('.loss').innerText = score.loss;
    document.querySelector('.ties').innerText = score.tie;

    localStorage.setItem("score", JSON.stringify(score));
}
