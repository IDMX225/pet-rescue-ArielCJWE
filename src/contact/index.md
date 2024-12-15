---
title: "Contact Us"
layout: "base.njk"
---
<style> 
  body {
  font-family: Arial, sans-serif;
  background-color: #BBDED6;
  margin: 0;
  padding: 0;
}

.container {
  width: 80%;
  margin: 0 auto;
}

h1 {
  margin: 0;
}

p{
  padding: 10px;
}

.contact-section {
  padding: 40px 0;
  text-align: center;
}

h2 {
  color: #333;
  margin-bottom: 20px;
  padding: 20px;
}

.form-container {
  background-color: #FAE3D9;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  margin-bottom: 40px;
  max-width: 600px;
  margin: 20px auto;
}

.form-container h3 {
  color: #333;
  margin-bottom: 15px;
}

.form-group {
  margin-bottom: 15px;
  text-align: left;
}

label {
  font-size: 1.1rem;
  color: #333;
}

input, textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 1rem;
}

button {
  background-color: #61c0bf;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  font-size: 1rem;
  cursor: pointer;
  width: 100%;
}

button:hover {
  background-color: #4fa59f;
}
</style>
<h2>We'd Love to Hear From You!</h2>
      <p>If you're interested in adopting or contacting us, please fill out one of the forms below:</p>

      <!-- Adopter Form -->
      <div class="form-container">
        <h3>Adopt a Pet</h3>
        <form id="adopter-form" action="/submit-adoption" method="POST">
          <div class="form-group">
            <label for="adopter-name">Full Name:</label>
            <input type="text" id="adopter-name" name="adopter-name" required>
          </div>

          <div class="form-group">
            <label for="adopter-email">Email Address:</label>
            <input type="email" id="adopter-email" name="adopter-email" required>
          </div>

          <div class="form-group">
            <label for="adopter-phone">Phone Number:</label>
            <input type="tel" id="adopter-phone" name="adopter-phone" required>
          </div>

          <div class="form-group">
            <label for="adopter-message">Why do you want to adopt a pet?</label>
            <textarea id="adopter-message" name="adopter-message" rows="4" required></textarea>
          </div>

          <button type="submit">Submit Adoption Application</button>
        </form>
      </div>

      <div class="form-container">
        <h3>Contact Us</h3>
        <form id="contact-form" action="/submit-contact" method="POST">
          <div class="form-group">
            <label for="contact-name">Full Name:</label>
            <input type="text" id="contact-name" name="contact-name" required>
          </div>

          <div class="form-group">
            <label for="contact-email">Email Address:</label>
            <input type="email" id="contact-email" name="contact-email" required>
          </div>

          <div class="form-group">
            <label for="contact-phone">Phone Number:</label>
            <input type="tel" id="contact-phone" name="contact-phone" required>
          </div>

          <div class="form-group">
            <label for="contact-message">Are you interested in scheduling a visit?</label>
            <textarea id="contact-message" name="contact-message" rows="4" required></textarea>
          </div>

          <button type="submit">Submit</button>
        </form>
      </div>
    </div>

