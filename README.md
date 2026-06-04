<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Registration Form</title>

<style>
    body{
        font-family: Arial, sans-serif;
        margin: 30px;
    }

    h1{
        font-size: 45px;
        margin-bottom: 10px;
    }

    hr{
        margin-bottom: 30px;
    }

    .form-group{
        margin-bottom: 25px;
    }

    label{
        display: block;
        font-size: 20px;
        margin-bottom: 8px;
    }

    input[type="text"],
    input[type="email"],
    input[type="date"],
    select,
    textarea{
        width: 350px;
        padding: 10px;
        font-size: 18px;
    }

    .radio-group{
        margin-top: 10px;
    }

    .radio-group label{
        display: block;
        margin-bottom: 10px;
        font-size: 18px;
    }

    textarea{
        height: 100px;
        resize: vertical;
    }

    button{
        padding: 10px 25px;
        font-size: 18px;
        cursor: pointer;
    }
</style>
</head>

<body>

<h1>Student Registration</h1>
<hr>

<form>

    <div class="form-group">
        <label>Name:</label>
        <input type="text" name="name">
    </div>

    <div class="form-group">
        <label>Email:</label>
        <input type="email" name="email">
    </div>

    <div class="form-group">
        <label>Course:</label>

        <div class="radio-group">
            <label><input type="radio" name="course"> HTML</label>
            <label><input type="radio" name="course"> CSS</label>
            <label><input type="radio" name="course"> JavaScript</label>
        </div>
    </div>

    <div class="form-group">
        <label>Gender:</label>

        <div class="radio-group">
            <label><input type="radio" name="gender"> Male</label>
            <label><input type="radio" name="gender"> Female</label>
        </div>
    </div>

    <div class="form-group">
        <label>Date of Birth:</label>
        <input type="date" name="dob">
    </div>

    <div class="form-group">
        <label>Mobile Number:</label>
        <input type="text" placeholder="Enter mobile number">
    </div>

    <div class="form-group">
        <label>Department:</label>
        <select>
            <option>Select Department</option>
            <option>Computer Science</option>
            <option>Information Technology</option>
            <option>Electronics</option>
            <option>Mechanical</option>
            <option>Civil</option>
        </select>
    </div>

    <div class="form-group">
        <label>Comments:</label>
        <textarea></textarea>
    </div>

    <button type="submit">Submit</button>

</form>

<hr>

</body>
</html>
