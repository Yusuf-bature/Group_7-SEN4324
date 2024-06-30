# Group_7-SEN4324 aliyu musa khalifa
html
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Complaints</title>
     <style>
          body{
               font-family: Arial, sans-serif;
               background: white;
               display: grid;
               justify-content: center;
               align-items: center;
               height: 100vh;
               margin: 0;
          }
         h1{
               margin: 0;
              
          }
          p{
               
               color: #666;
          }
          .hr{
               height: 5px;
               background-color: black;
              
          }
          .form-group{
               margin-bottom: 15px;
          }
          label{
               display: block;
               margin-bottom: 5px;
          }
          .required{
               color: red;
          }
          input[type="text"],
          input[type="email"],
          input[type="tel"],
          textarea {
               width: calc(100% - 20px);
               padding: 10px;
               border: 1px solid #ccc;
               border-radius: 4px;
          }
          .name-inputs{
               display: flex;
               justify-content: space-between;
               gap: 3%;
          }
          .name-inputs input{
               width: 48%;
          }
          button{
               width: 50%;
               padding: 10px;
               background-color: #f44336;
               color: white;
               border: none;
               border-radius: 4px;
               font-size: 16px;
               cursor: pointer;
               align-items: center;
               justify-content: center;
          }
     </style>
 
</head>
<body>
     <center>
          <h1>Complaints</h1>
          <p>Help us improve our service</p>
          <div class="hr1">
               <hr class="hr">
          </div>
     </center>
     <form>
          <div class="form-group">
               <label for="fname">Full name <span class="required">*</span></label>
               <div class="name-inputs">
                    <input type="text" id="first-name" placeholder="First" required>
                    <input type="text" id="last-name" placeholder="Last" required>
               </div>
          </div>
          <div class="form-group">
               <label for="email">Email: <span class="required">*</span></label>
               <input type="email" name="email" id="email" required>
          </div>
          <div class="form-group">
               <label for="phone">Phone:</label>
               <input type="tel" id="phone" name="phone">
          </div>
          <div class="form-group">
               <label for="complaint">Where did we go wrong? <span class="required">*</span></label>
               <textarea name="complaint" id="complaint" rows="4" required></textarea>
          </div>
          <center>
               <button type="submit" id="submit">Submit</button>
          </center>
     </form>
</body>
</html>


   1-Upadte inde.html => Made changes to the button width and padding 
   2- added a footer to the page 
   3- made changes to the footer class name
   4- made changes to the footer style
   5- made some changes in the entire login
   6- Added the email helper to the page

   
