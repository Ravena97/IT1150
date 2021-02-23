     <!DOCTYPE html>
        <html>
       <body>
       <style>
     body {background-color: Aqua;}

     input[type=text], select{
     width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    }

    input[type=submit] {
    width: 100%;
    background-color: #4CAF50;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    }

    input[type=submit]:hover {
    background-color: #45a049;
    }

    div {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
     }
    </style>


     <h3>Order your exotic friend here!</h3>

     <div>
    <form>
    
     <label for="fname">First Name</label>
     <input type="text" id="fname" name="firstname" placeholder="Your name.">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">
    
   

    <label for="animal">Animal</label>
    <select id="animal" name="animal">
      <option value="black panther">Black Panther</option>
      <option value="snake">Snake</option>
      <option value="iguana">Iguana</option>
      <option value="monkey">Monkey</option>
      
    </select>
  
    <input type="submit" value="Submit">
    </form>
    </div>
    </body>
    </html>
