<h1>Blog With Kumar</h1>

<h4>[ Tech stack: ]</h4>
<ul>
  <li>MongoDB for database</li>
  <li>Express, Node.js for backend</li>
  <li>multer for file uploading</li>
  <li>JwT for authentication</li>
  <li>bcrypt for password hashing</li>
  <li>ejs and bootstrap for frontend and design</li>
</ul>



<h4>[ Deployment pending!! ]</h4>
<h5>Once the design is perfect and some issues are resolved, this will be deployed as well</h5>

<p>Image: SignUp Page: Asks user for email,name and password. If the email is already registered redirects it to signin page else makes user account. The password is hashed before saving in the database. The password strength is also checked using Regex</p>
<img src="/images/9.jpg" width="600">
<img src="/images/1.jpg" width="600">


<p>Image: SignIn Page: Asks user for email and password. If email is not found in database redirects user to signup page else matches the entered password with the hashed one. If the password matching is successful it signs the user in else throw an error of whether the email is not registered or password not matched</p>
<img src="/images/10.jpg" width="600">
<img src="/images/2.jpg" width="600">

<p>Image: JwT tokens is used and saved in cookies for keeping the user login after the page is refreshed, basically for authentication purpose.Sample image is attached and ofcourse I will delete this user later from database</p>
<img src="/images/3.jpg" width="600">

<p>Image: After login the main homepage will be displayed where all the blogs written by different authors are listed. User can add or comment in any blog only after signin. The option for adding blog will be displayed on the top right side of screen once the user signin.</p>
<img src="/images/8.jpg" width="600">

<p>Image: The logged in user may add a blog by going on the Add Blogs page. Multer is used for uploading files, the user is supposed to enter the title and content of the blog in the upload blog page and the the blog is listed in the homepage with the latest blog on first</p>
<img src="/images/4.jpg" width="600">

<p>Image: Any signed in user can read blog written by anyone and comment on anyone's blog. User who don't have an account can only see the comments but cannot add any. They may however read the blogs written by anyone.</p>
<img src="/images/7.jpg" width="600">
