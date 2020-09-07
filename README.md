# FrissonKit-Beta-Official (5.0.4) New release.
FrissonKit is a advance CSS Framework. Which is developed by Shourov Roy under QuantumForte.com, and its the quick startup frame of FrissonKit officially for every latest updates.

Whats new in beta ~ 5.0.4 ??
1. Improved Button class.
2. Now you can use Button tag with the button class.
3. Forms are more rich design now. and "Tel" type is added.
4. Alert Module with close option.
5. Contain Div(s) side by side using the class="items-wrapper"

Bug fixes in beta ~ 5.0.4 :
1. class="btn", fixed the issue of button moving right side on hover.

Improvements ?
1. 20% Shorter code
2. More stable
3. More responsive
4. 99% no errors on console



Use of new Features?

1. How to use button in FrissonKit Beta ~ 5.0.4?
   * <button class="btn bg-night-5 bright"> Click here </button>
   * <a href="#" class="btn bg-night-5 bright"> Click here </a>
   Note: "btn" will make the shape of button, "bg-night-5" is the background color, "bright" is the text color
   
2. How to use form??
use this code to see the work >>>
            <form class="form">
                <label class="form-label" for="fname">First Name</label><br>
                <input type="text" id="fname" name="firstname" placeholder="Your name..">
  
                <label class="form-label" for="lname">Last Name</label><br>
                <input type="text" id="lname" name="lastname" placeholder="Your last name..">

                <label class="form-label" for="country">Country</label><br>
                <select class="drop-down-wrapper" id="country" name="country">
                    <option class="drop-down-item" value="australia">Australia</option>
                    <option class="drop-down-item" value="canada">Canada</option>
                    <option class="drop-down-item" value="usa">USA</option>
                </select>

                <label class="form-label" for="subject">Subject</label><br>
                <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

                <label class="form-label" for="datemax">Enter a date before 1980-01-01:</label>
                <input type="date" id="datemax" name="datemax" max="1979-12-31"><br><br>

                <label class="form-label" for="myfile">Select a file:</label>
                <input type="file" id="myfile" name="myfile">

                <label class="form-label" for="quantity">Quantity (between 1 and 5):</label>
                <input type="number" id="quantity" name="quantity" min="1" max="5">

                <label class="form-label" for="homepage">Add your homepage:</label>
                <input type="url" id="homepage" name="homepage">

                <label class="form-label" for="email">Email:</label> <br>
                <input type="email" id="email" placeholder="Enter email" name="email">
                <label class="form-label" for="pwd">Password:</label> <br>
                <input type="password" id="pwd" placeholder="Enter password" name="pswd">
                <input type="radio" id="male" name="gender" value="male">
                <label for="male">Male</label><br>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label><br>
                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label><br>
                <label class="">
                    <input type="checkbox" name="remember"> Remember me
                </label><br>
                <div class="form-btn-wrapper">
                    <input class="form-fill-btn bg-special-7" type="submit" value="Submit">
                    <input class="form-fill-btn bg-special-9" type="reset">
                </div>

            </form>
            
Note: "form" is the class to get in shape and "form-label" is to make the input title.       


3. How to you alert module?
use this code>>

    <div id="close" class="alert-bar bg-red-4 bright" style="border-radius: 0px !important;">
        <div class="alert-note">
            Most advanced FrissonKit donate us now
        </div>
        <div class="alert-times" onclick="kill()">
            <i class="fas fa-times-circle"></i>
        </div>
    </div>
    
Note: (id="close") is must to close the alert. "alert-bar" is the class to get in shape, "bg-red-4" is for making background color and "bright" is for the white color of the text. Then "alert-note" class is used to get in shape of the alert message, "alert-times" class is used to contain the (x) icon class and (<i class="fas fa-times-circle"></i>)
this is the font awesome class icon. Then {onclick="kill()"} option is used to make it close on click.


4. How to use "Items Wrapper"?

It used to make 2 things or elements side by side but make sure the items need to be in seperate div(s)
Example:
        
        <div class="items-wrapper">
          <!--1st div contains 1st element-->
          <div>
            <h2>This is the 1st item in 1st div </h2>
          </div>
          
          <!--2nd div contains 2nd element-->
          <div>
            <h2>This is the 2nd item in 2nd div </h2>
          </div>
        </div>

