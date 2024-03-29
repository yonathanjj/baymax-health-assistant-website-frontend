<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Baymax Symptom Checker</title>
  <link rel="stylesheet" href="{{ url_for('static', filename='website.css') }}">  </head>
<script src="{{ url_for('static', filename='website.js') }}"></script>
<img src="{{ url_for('static', filename='image/nurse1.jpg') }}">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <style>
  </style>
</head>
<body>
  <header class="container">
    <nav class="navbar">
      <a href="#">Signup/Login</a>
      <a href="#">Features</a>
      <a href="#">Services</a>
      <a href="#">Testimonials</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
      <p class="big-red-text">Welcome to Baymax.bt, the only doctorbot you'll need</p>
    <div class="hero">
      <h1>Transforming healthcare with innovative solutions</h1>
      <p>Baymax.bt is dedicated to enhancing health and well-being through advanced technology and personalized care. We provide accurate diagnoses and effective treatments, empowering you to take control of your health journey.</p>
    </div>
  </header>

  <main class="container">
    <section class="signup-form">
      <p class="greeting">Hello there! Sign up here or log in if you have an account.</p>
      <form action="#">
        <div class="input-field">
          <label for="email">Email:</label>
          <input type="email" id="email" placeholder="Enter your email">
        </div>
        <div class="input-field">
          <label for="password">Password:</label>
          <input type="password" id="password" placeholder="Enter your password">
        </div>
        <div class="button-group">
          <button class="btn-signup">Sign up</button>
          <button class="btn-login">Login instead</button>
        </div>
        <script>


        </script>
      </form>
      <img src="image/long picture.jpg" alt="animated illustration" class="a man surrounded by doctors">
    </section>

    <section class="services">
      <div class="service">
        <img src="image/nurse1.jpg" alt="women nurse">
        <p>Health bot - Customized Treatment Plans</p>
      </div>
      <div class="service">
        <img src="image/nurse2.jpg" alt="a doctor standing">
        <p>Expert Medical Professional Bot</p>
      </div>
      <div class="service">
        <img src="image/nurse3.jpg" alt="girl running">
        <p>Advanced Diagnostics & Precision Care</p>
      </div>
    </section>

    <section id="symptom-checker">
      <h1>Baymax Symptom Checker</h1>
      <p>Select your symptoms to get a list of potentially related illnesses. **Disclaimer:** This is for informational purposes only. Always consult a healthcare professional for diagnosis and treatment.</p>

      <p class="not-signed-up">**Please sign up or log in to use the symptom checker.**</p>
    <div class="symptom-category">
        <h3>General</h3>
        <label><input type="checkbox" name="general" value="fever"> Fever</label>
        <label><input type="checkbox" name="general" value="fatigue"> Fatigue</label>
        <label><input type="checkbox" name="general" value="malaise"> Malaise</label>
        <label><input type="checkbox" name="general" value="weight loss"> Weight Loss</label>
        <label><input type="checkbox" name="general" value="night sweats"> Night Sweats</label>
    </div>

    <div class="symptom-category">
        <h3>Respiratory</h3>
        <label><input type="checkbox" name="respiratory" value="cough"> Cough</label>
        <label><input type="checkbox" name="respiratory" value="shortness of breath"> Shortness of Breath</label>
        <label><input type="checkbox" name="respiratory" value="sore throat"> Sore Throat</label>
        <label><input type="checkbox" name="respiratory" value="chest pain"> Chest Pain</label>
        <label><input type="checkbox" name="respiratory" value="wheezing"> Wheezing</label>
    </div>

      <div class="symptom-category">
        <h3>Cardiovascular</h3>
        <label><input type="checkbox" name="cardiovascular" value="chest pain"> Chest Pain</label>
        <label><input type="checkbox" name="cardiovascular" value="shortness of breath"> Shortness of Breath</label>
        <label><input type="checkbox" name="cardiovascular" value="palpitations"> Palpitations</label>
    </div>

      <div class="symptom-category">
        <h3>Neurological</h3>
        <label><input type="checkbox" name="neurological" value="headache"> Headache</label>
        <label><input type="checkbox" name="neurological" value="dizziness"> Dizziness</label>
        <label><input type="checkbox" name="neurological" value="confusion"> Confusion</label>
    </div>


    <div class="related-illness">
        <h3>Stroke</h3>
        <label><input type="checkbox" name="stroke" value="sudden numbness"> Sudden numbness or weakness</label>
        <label><input type="checkbox" name="stroke" value="confusion"> Confusion</label>
        <label><input type="checkbox" name="stroke" value="trouble speaking"> Trouble speaking</label>
        <label><input type="checkbox" name="stroke" value="trouble walking"> Trouble walking</label>
    </div>

         <div class="symptom-category">
        <h3>Dermatological</h3>
        <label><input type="checkbox" name="dermatological" value="rash"> Rash</label>
        <label><input type="checkbox" name="dermatological" value="itching"> Itching</label>
        <label><input type="checkbox" name="dermatological" value="skin lesions"> Skin Lesions</label>
    </div>


    <div class="related-illness">
        <h3>Eczema</h3>
        <label><input type="checkbox" name="eczema" value="itching"> Itching</label>
        <label><input type="checkbox" name="eczema" value="rash"> Rash</label>
        <label><input type="checkbox" name="eczema" value="dry skin"> Dry Skin</label>
    </div>

    <div class="related-illness">
        <h3>Malaria</h3>
        <label><input type="checkbox" name="malaria" value="headache"> Headache</label>
        <label><input type="checkbox" name="malaria" value="fever"> Fever</label>
        <label><input type="checkbox" name="malaria" value="chills"> Chills</label>
        <label><input type="checkbox" name="malaria" value="sweating"> Sweating</label>
    </div>

    <div class="related-illness">
        <h3>Common cold</h3>
        <label><input type="checkbox" name="common cold" value="cough"> Cough</label>
        <label><input type="checkbox" name="common cold" value="sore throat"> Sore Throat</label>
        <label><input type="checkbox" name="common cold" value="runny nose"> Runny Nose</label>
        <label><input type="checkbox" name="common cold" value="congestion"> Congestion</label>
    </div>

     <div class="related-illness">
        <h3>Heart Disease</h3>
        <label><input type="checkbox" name="heart disease" value="chest pain"> Chest Pain</label>
        <label><input type="checkbox" name="heart disease" value="shortness of breath"> Shortness of Breath</label>
        <label><input type="checkbox" name="heart disease" value="fatigue"> Fatigue</label>
    </div>
           <form id="symptomsForm">
  <button type="submit">Submit Symptoms</button>
</form>
<div id="waitingModal" class="modal">
  <div class="modal-content">
    <p>Processing your request...</p>
  </div>
</div>
<span id="loadingSpinner" style="display: none;"><i class="fa fa-spinner fa-spin"></i></span>
<h2>Response from Baymax:</h2>
<div id="baymax-response" class="baymax-response-box">
  <span class="baymax-text"></span>
</div>
    </section>

        <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
  <link rel="stylesheet" href="website.css">
  <script src="website.js"></script>
  <style>
  </style>
</head>
<body>

  <main class="container">
    <section>
           <h2>About</h2>
      <p>Welcome to Baymax.bt, your dedicated healthcare companion that is revolutionizing the way you manage your
        health. Our platform provides an innovative solution for individuals seeking accurate diagnoses and personalized
        care. By registering on our website, you gain access to a powerful symptom checker that empowers you to take
        control of your health journey. Simply select the symptoms you are experiencing, and our advanced algorithm will
        analyze the data to provide you with a list of potential illnesses that match your symptoms. It's like having a
        virtual medical professional at your fingertips. However, please note that the information provided by Baymax.bt
        is for informational purposes only and should not replace professional medical advice. We always recommend
        consulting a healthcare professional for an accurate diagnosis and appropriate treatment. Join Baymax.bt today
        and unlock a new level of healthcare convenience and knowledge!</p>
      <p>
        <</section>
    <section>
      <h2>Contact</h2>
      <p>Email: baymaxbt@gmail.com</p>
      <p>Phone: +2519-4565-7890</p>
    </section>
  </main>

  <footer class="container">
    <p>&copy; 2024 My Web Page. All rights reserved.</p>
  </footer>
</body>
  </main>
</html>
