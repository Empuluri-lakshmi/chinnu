

<html>
 <head>
  <style>
   div
    {
     border-top:3px solid grey;
     border-right:3px solid black;
     border-bottom:3px solid black;
     border-left:3px solid grey;
     width:275px;
     padding:2px;
    }
   .l
     {
      border:20px solid lightblue;
      width:250px;
      text-align:center;
      padding:10px;
     }
  </style>
 </head>
 <body>
  <form action="test.php" method="GET" target="_blank">
  <div>
  <fieldset style="border:1px solid black;">
   <label>Name:</label>
   <input type="text" name="username" id="name" />
   <br/><br/>
   <label>Surname:</label>
   <input type="text" name="name" id="name" />
   <br/><br/>
   <input type="radio" name="male" id="gender" />
   <label>Male</label>
   <input type="radio" name="female" id="gender" />
   <label>Female</label>
   <br/><br/>
   <label>Class:</label>
   <select name="class">
    <option value="puc1">PUC1</option>
    <option value="puc2">PUC2</option>
   </select>
   <input type="submit" value="submit" />
   </fieldset>
   </div>
   <br/><br/>
   <table border="1" bgcolor="gray" width="45%">
    <tr>
    <td>ID Number:</td>
    <td><input type="text" name="id" id="id" /></td>
   </tr>
   <tr>
    <td>Name:</td>
    <td><input type="text" name="name" id="name" /></td>
   </tr>
   <tr>
    <td colspan="2">Address:<textarea rows="4" cols="25"></textarea>
    </td>
   </tr>
   <tr align="center">
    <td colspan="2"><input type="submit" value="submit" /></td>
   </tr>
  </table>
   <p class="l"><font color="lightblue">Login To Your Account</font>
   <br/><br/>
   <input type="text" placeholder="Username" />
   <br/><br/>
   <input type="password" placeholder="Password" />
   <br/><br/>
   <button style="background-color:lightblue;width:155px;color:white;border:none;">Login</button>
   </p>
   <fieldset>
    <legend>Personalia:</legend>
    <label>First name:</label>
    <input type="text" name="name" id="name" />
    <br/><br/>
    <label>Last name:</label>
    <input type="text" name="name" id="name" />
     <br/><br/>
     <label>Email:</label>
     <input type="email" name="email" id="email" />
      <br/><br/>
      <label>Birthday:</label>
      <input type="date" name="bd" id="bd" />
      <br/> <br/>
      <input type="submit" value="submit" />
      </fieldset>
      <br/><br/>
      <input type="checkbox" name="game" id="game" />
      <label>Cricket</label>
      <br/><br/>
      <input type="checkbox" name="game" id="game" />
      <label>Volleyball</label>
      <br/><br/>
      <input type="checkbox" name="game" id="game" />
      <label>Badminton</label>
      <br/><br/>
      <label>Email:</label>
      <input type="email" name="mail" id="mail" />
      <br/><br/>
      <label>Upload-file:</label>
      <input type="file" name="file" id="file" />
      <br/><br/>
      <input type="reset" value="reset" />
  </form>
 </body>
</html>
