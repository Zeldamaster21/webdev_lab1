<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Document</title>
</head>
<body>
  <h1>RSVP form</h1>
  <form action="http://bloomingdale.sat.iit.edu/kriedan/lab3formscript.php" method="post">
    <fieldset>
      <legend>Your Info</legend>
      <div><label>first name: <input size="100" type="text" name="first_name_field"></label></div>
      <div><label>last name: <input size="100" type="text" name="last_name_field"></label></div>
      <div><label>phone: <input size="100" type="text" name="phone_field"></label></div>
      <div><label>email: <input size="100" type="text" name="email_field"></label></div>
      <div><label>people: <input size="100" type="text" name="people_field"></label></div>
      <div>Gender: </div>
      <div>
        <label>Male <input type="radio" name="gender_field" value="male"></label>
        <label>Female <input type="radio" name="gender_field" value="female"></label>
      </div>
      <div>Age: </div>
      <select name="age_field">
        <option>under 18</option>
        <option>over 18</option>
      </select>
    </fieldset>
    <fieldset>
      <legend>Availability</legend>
      <h3>Days Available:</h3>
      <div>
        <div><label>Sunday <input type="checkbox" name="available_field[]" value="sunday"></label></div>
        <div><label>Saturday <input type="checkbox" name="available_field[]" value="saturday"></label></div>
        <h3>Food selection</h3>
        <div><label>Steak <input type="checkbox" name="Food selection_field[]" value="Steak"</label></div>
         <div><label>Chicken <input type="checkbox" name="Food selection_field[]" value="Chicken"</label></div>
        <h4> Steak prefrence</h4>
         <div><label>Rare <input type="checkbox" name="steakprefrence_field[]" value="rare"</label></div>
         <div><label>Medium <input type="checkbox" name="steakprefrence_field[]" value="medium"</label></div>
          <div><label>Well Done <input type="checkbox" name="steakprefrence_field[]" value="well Done"</label></div>
          <div><label>none <input type="checkbox" name="steakprefrence_field[]" value="none"</label></div>
        <h3>Comments</h3>
        <textarea name="comments_field"></textarea>
      </div>
    </fieldset>
    <input type="hidden" name="hidden_field" value="dkriegls">
    <input type="submit">
  </form>
</body>
</html>
