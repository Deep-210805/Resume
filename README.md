<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student survey Form</title>
    <style>
        .web{
            position: relative ;
            background-color: rgb(128, 128, 128);
            border: solid 8px black;
            margin-bottom: 5px;
            padding: 15px;
            text-align:justify;
        }
        .outerpage{
            border: solid black;
            background-color:gray;
            box-shadow : 9px 13px 14px rgba(1,1,3,0.7);
        }
    </style>
</head>
<body><div class="web">
    <div class="heading">
        <h1>Student Survey Form</h1>
    </div>
    <div class="outerpage">
        <form id="form">
<div id="form-control">
    <p>Name</p>
    <input type="text" placeholder="Enter your name :" width="95%">
    <p>Phone number</p>
    <input type="tel" placeholder="Enter phone number :">
    <p> Enter Your date of birth :</p>
    <input type="date">
</div>
<div id="pursuing">
<p>
    You are currently pursuing :
</p>
<select>
    <option>B.tech/B.E</option>
    <option>Mbbs</option>
    <option>Bds</option>
    <option>Bsc</option>
    <option>other</option>
</select>
</div>
<div id="rank">
    <p>
        What is your rank in Jee/Neet(if given) :
    </p>
    <select>
        <option value="option 1">1-1000</option>
        <option value="option 2">1000-5000</option>
        <option value="option 3">5000-15000</option>
        <option value="option 4">15000-20000</option>
        <option value="option 5">>20000</option>
    </select>
</div>
<div id="college">
    <p>
        Is your college as per your dreams:
    </p>
    <input type="radio" id="option1">  <label for="option1">Yes</label>
    <input type="radio" id="option2"><label for="option2">No</label>
    <input type="radio" id="option3">  <label for="option3">Prefer not to say</label>
</div>
<div>
    <p>
Is online study helpful for you ?
    </p>
    <input type="checkbox" id="opt1"><label for="opt1">yes</label>
    <input type="checkbox" id="opt1"><label for="opt2">No</label>
</div>
<div id="suggestion">
    <p>How frequently you used phone while your preperation :</p>
    <input type="time" id="54"><label for="54">Enter in hr:min</label>
</div>
<div>
    <p>
        Would you want to give any suggestion to your juniors :
    </p>
    <textarea placeholder="write 3,4 lines from your Experience..." cols="20" rows="6"></textarea>
</div><br>
<br>
<div id="Submit">
    <a href="Image1.png">Submit Your responses</a>
    <br>
    <br>
    <br>
</div>
    </div></form>
</div>
</body>
</html>
