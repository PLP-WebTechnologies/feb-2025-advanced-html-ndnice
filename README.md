<!DOCTYPE html>
<html>
    <head>
        <body>
            <title>
                <head>Week 2 Assignment</head>
            </title>
        <h1>Ordered List with Roman Numericals</h2>
        <ol type="I">
            <li>Nigeria</li>
            <li>Ghana</li>
            <li>Cameroon</li>
            <li>Kenya</li>
        </ol>
        <h2>External image</h2>
        <img src="https://www.pexels.com/photo/jellyfish-in-the-dark-with-a-black-background-17728360/" alt="Image of life" height="300" width="300">
        <h3>Contact information</h3>
        <table border="2">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Nnamdi</td>
                    <td>32, Epetedo street Ogudu,Nigeria</td>
                    <td>08138324317</td>
                    <td>ns.nnamdi@gmail.com</td>
                </tr>
                <tr>
                    <td>Kelvin</td>
                    <td>31, Epetedo Street Ogudu, Lagos Nigeria</td>
                    <td>083426132731</td>
                    <td>ns,sddydudu@gmail.com</td>
                </tr>
                <tr>
                    <td>Jude</td>
                    <td>30, Epetedo Street Ogudu, Lagos Nigeria</td>
                    <td>81326413275</td>
                    <td>jude@gmail.com</td>
                </tr>
                <tr>
                    <td>Kunle</td>
                    <td>29, Epetedo Street Ogudu, Lagos Nigeria</td>
                    <td>81324531753</td>
                    <td>kunle@gmail.com</td>
                </tr>
                <tr>
                    <td>Seyi</td>
                    <td>28, Epetedo Street Ogudu, Lagos Nigeria</td>
                    <td>08234567832</td>
                    <td>seyi@yahoo.com</td>
                </tr>   
            </tbody>
        </table>
       <h3>Registration forms</h3>
       <form action="">
       <label for="full_name">Full Name</label>
        <input type="text" name="full_name" id="full_name" required placeholder="Enter your full_name" Required>
        <br><br>
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="nnamdi@example.com" required>
        <br><br>
        <label for="Password">Password</label>
        <input type="password" id="password" name="password" placeholder="Your password" required>
        <br><br>
        <label for="date">Date</label>
        <input type="date" name="Date" id="date" placeholder="Date" required>
        <br><br>
    </form> 
    <br><br>
    <label for="gender">Gender</label>
    <input type="radio" name="gender" value="female"> Female
    <input type="radio" name="gender" value="male"> Male
    <br><br>
    <label for="hobby">Hobbies</label>
    <input type="checkbox" name="hobby" value="travel"> travel
    <input type="checkbox" name="hobby" value="music"> music
    <input type="checkbox" name="hobby" value="reading"> reading
    <input type="checkbox" name="hobby" value="swimming"> swimming
   <br><br>
   <label>Country</label>   
   <select name="country" id="country">
    <option>--Select Country--</option>
    <option value="South Africa">South Africa</option>
    <option value="Ghana">Ghana</option>
    <option value="Tanzania">Tanzania</option>
    <option value="Guinea">Guinea</option>
   </select>  
   <br><br>
   <button type="submit">Submit</button>
    <input type="reset" value="Cancel/reset">
    </body>
    </head>
</html>
