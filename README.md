# Quiz_page
#HTML

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="quiz-questions-top-container">
        <h1 class="quiz-questions-top-score">Score: 25/45</h1>

        <div class="quiz-questions-top-card-container">
            <h1 class="quiz-questions-top-card-heading">Question 10</h1>
            <p class="quiz-questions-top-card-para">Which of the following content of the HTML paragraph element?</p>
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/coding-question-img.png" class="quiz-questions-top-card-image" />
        </div>

        <div class="quiz-questions-bottom-card-container">

            <ul class="unordered-list-type">
                <li class="quiz-questions-bottom-card-boxes">A. HTML heading elements</li>
                <li class="quiz-questions-bottom-card-boxes">B. HTML paragraph elements</li>
                <li class="quiz-questions-bottom-card-boxes-selected">C. This is paragraph...</li>
                <li class="quiz-questions-bottom-card-boxes">D. None of the above</li>
            </ul>
            <button class="quiz-questions-bottom-card-button">Submit</button>
        </div>
    </div>
</body>
</html>

#CSS

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');


.quiz-questions-top-container {

    background-color: #875fc0;
    background-size: cover;

}

.quiz-questions-top-score {

    color: white;
    font-weight: bold;
    text-align: right;
    font-size: 20px;
    padding: 20px;

}

.quiz-questions-top-card-container {

    background-color: white;
    text-align: center;
    margin: 25px;
    padding: 10px;
    border-radius: 25px;

}

.quiz-questions-top-card-heading {

    font-size: 28px;

}

.quiz-questions-top-card-para {


    font-size: 18px;
}

.quiz-questions-top-card-image {

    height: 120px;
}

.quiz-questions-bottom-card-container {

    background-color: white;
    margin: 20px;
    border-radius: 20px;
    padding: 20px;
    text-align: center;
}

.unordered-list-type {

    list-style-type: none;
}

.quiz-questions-bottom-card-boxes {
    border-style: solid;
    height: 45px;
    width: 260px;
    padding: 10px;
    margin: 10px;
    border-radius: 10px;
    margin-left: 50px;
    text-align: start;
}

.quiz-questions-bottom-card-boxes-selected {

    border-style: solid;
    height: 45px;
    width: 260px;
    padding: 10px;
    margin: 10px;
    border-radius: 10px;
    margin-left: 50px;
    background-color: #875fc0;
    color: white;
    text-align: start;
}

.quiz-questions-bottom-card-button {

    height: 35px;
    width: 100px;
    background-color: #fbaf00;
    border-radius: 8px;
    border-width: 0px;
    color: white;
}
