# Order-Summary-Component
Solution to Order Summary Component

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | Order summary card</title>
    <link rel="stylesheet" type="text/css" href="styles.css" />
    <!--BOOTSTRAP-->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ"
      crossorigin="anonymous"
    />
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
      crossorigin="anonymous"
    ></script>
  </head>
  <style>
  @import url("https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap");

.attribution {
  font-size: 15px;
  text-align: center;
  margin-top: 10rem;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}

html body {
  background-color: hsl(225, 100%, 94%);
}

body {
  background-image: url(images/pattern-background-desktop.svg);
  background-repeat: no-repeat;
  background-size: 100% auto;
}
.card {
  margin-left: 45rem;
  margin-top: 20rem;
  width: 50vh;
}

.card-body {
  height: 50vh;
  text-align: center;
}

.card-title {
  font-family: "Red Hat Display", sans-serif;
  font-weight: 900;
  font-size: 30px;
  margin-top: 2rem;
}

.card-text {
  margin-top: 2rem;
  font-family: "Red Hat Display", sans-serif;
  font-size: 16px;
  font-weight: 500;
  color: hsl(224, 23%, 55%);
}

.box {
  margin-left: 2.5em;
  margin-top: 1em;
  height: 6em;
  width: 22em;
  border-radius: 15px;
  background-color: hsl(225, 100%, 98%);
}

.music-icon {
  margin-top: 1.5em;
  margin-right: 16em;
}

.plan {
  margin-top: -3em;
  margin-right: 5em;
  font-size: 16px;
  font-family: "Red Hat Display", sans-serif;
  font-weight: 700;
}

.plan-price {
  margin-right: 5em;
  font-size: 16px;
  font-family: "Red Hat Display", sans-serif;
  color: hsl(224, 23%, 55%);
}

.link {
  display: block;
  margin-left: 18em;
  margin-top: -3.5em;
  font-family: "Red Hat Display", sans-serif;
  color: hsl(245, 75%, 52%);
  font-weight: 700;
  font-size: 14px;
  transition: all 0.1s ease-in-out;
}

#pay-btn {
  margin-top: 2em;
  margin-left: 0.1em;
  height: 3em;
  width: 25em;
  border-radius: 10px;
  background-color: hsl(245, 75%, 52%);
  color: white;
  font-family: "Red Hat Display", sans-serif;
  font-weight: 700;
  line-height: 2;
  font-size: 14px;
}

.btn-cancel {
  line-height: 5;
  margin-top: 20rem;
  text-decoration: none;
  font-family: "Red Hat Display", sans-serif;
  color: hsl(224, 23%, 55%);
  font-weight: 900;
  font-size: 15px;
}

/**ACTIVE STATES**/

.link:hover {
  text-decoration: none;
  color: hsla(245, 75%, 52%, 0.807);
}

#pay-btn:hover {
  background-color: hsla(245, 75%, 52%, 0.807);
}

.btn-cancel:hover {
  color: black;
}

.btn-cancel:hover {
  color: black;
}

@media (max-width: 1440px) {
  .attribution {
    font-size: 15px;
    text-align: center;
    margin-top: 10rem;
    margin-left: 10em;
  }
  .attribution a {
    color: hsl(228, 45%, 44%);
  }

  .card {
    margin-left: 35rem;
    margin-top: 10rem;
    width: 50vh;
  }

  .card-body {
    height: 50vh;
    text-align: center;
  }

  .card-title {
    font-family: "Red Hat Display", sans-serif;
    font-weight: 900;
    font-size: 30px;
    margin-top: 2rem;
  }

  #pay-btn {
    margin-left: 1em;
  }
}

@media (max-width: 375px) {
  .attribution {
    font-size: 15px;
    text-align: center;
    margin-left: -0.5em;
    margin-top: 4em;
  }
  .attribution a {
    color: hsl(228, 45%, 44%);
  }

  body {
    background-image: url(images/pattern-background-desktop.svg);
    background-repeat: no-repeat;
    background-size: 100% auto;
  }

  .card {
    margin-left: 1.5rem;
    margin-top: 5rem;
    width: 45vh;
  }

  .card-body {
    height: 50vh;
    text-align: center;
  }

  .card-title {
    margin-top: 1em;
    font-size: 22px;
  }
  .card-text {
    margin-top: 1em;
    font-size: 15px;
  }

  .box {
    margin-top: 1.5em;
    margin-left: 0.5em;
    height: 4.5em;
    width: 17em;
  }

  .music-icon {
    margin-top: 0.7em;
    margin-left: 1em;
  }

  .plan,
  .plan-price {
    margin-left: 3.5em;
  }

  .link {
    margin-top: -4em;
    margin-left: 14em;
    font-size: 13px;
  }

  #pay-btn {
    margin-top: 1em;
    margin-left: 0.5em;
    width: 19.5em;
  }

  .btn-cancel {
    display: block;
    margin-top: -1em;
    font-size: 15px;
  }
}

  </style>
  <body>
    <header></header>
    <main>
      <div class="card rounded-5">
        <img
          src="images/illustration-hero.svg"
          class="card-img-top rounded-top-4"
          alt="hero"
        />
        <div class="card-body">
          <h5 class="card-title">Order Summary</h5>
          <p class="card-text">
            You can now listen to millions of songs,<br />
            audiobooks, and podcasts on any device<br />
            anywhere you like!
          </p>
          <div class="box shadow-sm">
            <img
              class="music-icon"
              src="images/icon-music.svg"
              alt="music-icon"
            />
            <h5 class="plan">Annual Plan</h5>
            <p class="plan-price">$59.99/year</p>
            <a href="#" class="link">Change</a>
          </div>
          <a href="#" class="btn shadow-lg" id="pay-btn"
            ><span class="btn-text">Proceed to Payment</span></a
          >
          <br />
          <a href="#" class="btn-cancel">Cancel Order</a>
        </div>
      </div>
    </main>
    <footer>
      <div class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
          >Frontend Mentor</a
        >. Coded by <a href="https://github.com/Wagon706">Wagon706/guido</a>.
      </div>
    </footer>
  </body>
</html>
