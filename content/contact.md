+++
date = ""
tags = []
title = "Contact"

+++
 <style>
      input, textarea { 
      outline: none;
      }
      button {
      width: 100%;
      padding: 10px;
      margin-top: 20px;
      border-radius: 20px;
      border: none;
      border-bottom: 4px solid #3e4f24;
      background: #5a7233; 
      font-size: 16px;
      font-weight: 400;
      color: #fff;
      }
      button:hover {
      background: #3e4f24;
      } 
      @media (min-width: 568px) {
      form {
      width: 60%;
      }
      }
 </style>
    
<form name="Contact Aizera" method="POST" netlify> <p> <label>Name: <input type="text" name="Name:" required></label>  
</p>
<p>
<label>IGN: <input type="text" name="IGN:" required></label>  
</p>
<p>
<label>Discord Tag (Name#0000): <input type="text" name="Discord:" required></label>
</p>
<p>	<label>Message (Optional): <textarea name="message"></textarea></label>
</p>
<p>
<button type="submit">SUBMIT</button>
</p>
</form>