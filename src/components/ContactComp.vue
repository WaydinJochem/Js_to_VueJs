<template >
     <section id="contact">
      <form action="https://formspree.io/f/mqkorbqv" method="POST">
        <div>
          <label>
            Contact Number:
            <input type="tel" name="phone-number" placeholder="input contact number" minlength="9" maxlength="13" required>
          </label>
        </div>
        <div>
          <label>
            Email:
            <input type="email" name="email" placeholder="input email-address" required>
          </label>
        </div>
        <div>
          <label>
            Your message:
            <textarea name="message" cols="30" rows="6" placeholder="Input Text Messsage" required></textarea>
          </label>
        </div>
        <div>
          <button type="submit" id="sub-btn">Send</button>
        </div>
      </form>
    </section>
</template>
<style scoped>
     #contact {
  background-image: radial-gradient(purple,black);
  border-radius: 20px;
  margin: 5%;
  padding: 0.8% ;
  text-align: center;
  color: white;
 }
 div label {
  display: flex;
  flex-direction: column;
  align-items: center;
 }
 form div {
  margin-top: 1%;
 }
 label input {
  text-align: center;
  padding: 0.3%;
  font-size: large;
  border-radius: 20px;
 }
 label textarea {
  text-align: center;
  padding: 0.3%;
  font-size: large;
  resize: none;
  border-radius: 20px;
 }
 #sub-btn {
  border-radius: 20px;
  background-color: transparent;
  color: white;
 }
 #sub-btn:hover {
  font-size: large;
  background-image: linear-gradient(purple, violet);
 }
</style>