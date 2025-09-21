<!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Hotel Feedback Forn </title>
    </head><body>
         <header><h1>Hotel Feedback Form</h1>
    <p>Thank you for staying with us. Please provide feedback on your recent stay.</p></header>
   
      <main>
         <form method="POST" action="https://hotel-feedback.freecodecamp.org"" >
          <fieldset><legend>Personal Information</legend>
            <label for="full-name">Name (required):</label>
          <input type="text" id="full-name" name="name" placeholder="Ex. John Doe" reuired size="20">
            <label for="age">Age (optional):</label>
            <input type="number" id="age" name="age" min="3" max="100">
          <label for="email">Email (required):</label>
          <input type="email" id="email" name="email" placeholder="example@email.com" required size="20">
          </fieldset>
           <fieldset><legend>Was this your first time at our hotel?</legend>
              <input type="radio" id="yes-option" name="hotel-stay">
          <label for="yes-option">Yes </label>
                <input id="no-option" type="radio" name="hotel-stay">
          <label for="no-option">No </label>
           </fieldset>
           <fieldset><legend>Why did you choose to stay at our hotel? (Check all that apply)</legend>
          <input type="checkbox" name="ads" id="ads" value="ads">
          <label for="ads">Social Media Ads </label>
           <input type="checkbox" id="recommendation" name="recommendation" value="recommendation">
        <label for="recommendation">Personal Recommendation </label>
            <input type="checkbox" id="location" name="location" value="location">
          <label for="location">Location </label>
          <input checked type="checkbox" id="reputation" name="reputation" value="reputation">
          <label for="reputation">Reputation </label>
           <input type="checkbox" id="price" name="price" value="price">
          <label for="price"> Price </label>
          </fieldset>
           <fieldset><legend>Ratings</legend>
      <label for="service">How was the service?</label>
      </fieldset>
         </form>
      </main>
      </body>
