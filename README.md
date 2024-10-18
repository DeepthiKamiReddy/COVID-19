HTML CODE: 

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="covid-container">
        <div class="covid-header d-flex flex-row">
            <div>
                <h1 class="covid-heading-text">All you need to know COVID-19</h1>
                <button class="button">know more</button>
            </div>
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/medicalcare-img.png" />
        </div>
        <div class="covid-card-container covid-test-bg d-flex flex-row">
            <img class="covid-card-image" src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/coronavirus-img.png" />
            <div class="covid-card-text-container">
                <h1 class="covid-card-heading">
                    COVID-19 text
                </h1>
                <p class="covid-card-description">
                    if you think you have been exposed to novel coronavirus (COVID-19)....more
                </p>
            </div>
        </div>
        <h1 class="sub-heading">symptoms</h1>
        <div class="d-flex flex-row">
            <div class="covid-card-container cough-symptom-bg">
                <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/fever-img.png" />
                <p class="symptom-text">dry cough</p>
            </div>
            <div class="covid-card-container fever-symptom-bg">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/fever-img.png" />
                <p class="symptom-text">high fever</p>
            </div>
            <div class="covid-card-container headache-symptom-bg">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/headache-img.png" />
                <p class="symptom-text">headache</p>
            </div>
        </div>
        <h1 class="sub-haeding">video</h1>
        <div class="covid-card-container covid-video-bg d-flex flex-row">
            <img class="covid-card-image" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/doctor-img.png" />
            <div class="covid-card-text-container">
                <h1 class="covid-card-heading">
                    to prevent the spread of ...
                </h1>
                <p class="covid-card-heading">
                    if you think you have been exposed to novel corona corona virus
                    (COVID-19)
                </p>
                <button class="button">
                    watch video
                </button>
            </div>
        </div>


    </div>
        </div>
</body>

</html>


CSS CODE: 

@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.covid-container {
    border-style: solid;
    border-width: 5px;
    border-color: #0967d219;
}

.covid-header {
    margin: 15px;
}

.covid-heading-text {
    color: #323f4b;
    font-family: "roboto";
    font-size: 18px;
    font-weight: 500;
}

.button {
    color: #ffffff;
    background-color: #0967d2;
    font-family: "roboto";
    font-size: 12px;
    font-weight: 500;
    width: 85px;
    height: 30;
    border-width: 0px;
    border-radius: 8px;
}

.covid-card-container {
    border-radius: 12px;
    padding: 10px;
    margin: 10px;
}

.covid-text-bg {
    background-color: #0967d219;
}

.covid-card-image {
    width: 48px;
    height: 48px;
    margin: 10px;
}

.covid-card-text-container {
    padding: 5px;
}

.covid-card-heading {
    color: #323f4b;
    font-family: "roboto";
    font-size: 16px;
    font-weight: 500;
}
