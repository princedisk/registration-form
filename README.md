
<!DOCTYPE html>
<html>

<head>
<style>
        body {
            background-color: #f0f0f0;
            position: relative;
            margin: 0;
            padding: 0;
        }

        /* Diagonal watermark text */
        body::before {
            content: "REGISTRATION FORM";
            font-size: 60px;
            /* big text */
            color: rgba(246, 244, 244, 0.929);
            /* faint watermark */
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -70%) rotate(-45deg);
            /* diagonal */
            z-index: -1;
            /* behind everything */
            white-space: nowrap;
        }
    </style>
    <title>REGISTRATION FORM</title>
</head>

<body style="background-color: rgba(216, 216, 214, 0.926);">
<!--for page colour-->
<form>
    <!--for form-->
    <table align="center" width="700" cellpadding="30">
        <tr>
            <!--for a single line-->
            <td colspan="2" align="center">
                <h1 style="border:solid #180305; background-color: rgb(239, 237, 234);">REGISTRATION FORM</h1>
        </tr>
        <tr>
            <td>
                <h2>Your Name :</h2>
            </td>
            <td><input type="text" size="20" colspan="5" placeholder="first name " style="width: 150px;height:30px" />
                <input type="text" size="20" placeholder="Middle name" style="width: 150px;height:30px" />
                <!--to fetch name of the user-->
            </td>
        </tr>
        <tr>
            <td>
                <h2>Father's Name :</h2>
            </td>
            <!--fathers name-->
            <td><input type="text" size="30" placeholder="Father's name" style="width:200px;height:30px" /></td>
        </tr>
        <tr>
            <td>
                <h2>Mother's Name :</h2>
            </td>
            <!--mothers name-->
            <td><input type="text" size="30" placeholder="Mother's name" style="width:200px;height:30px" /></td>
        </tr>
        <tr>
            <!--date of birth-->
            <td style="font-weight: bold;font-size:14px">
                <h2>Date Of Birth :
            </td>
            <td><input type="date" style="width:200px;height:30px" /></td>
        </tr>

        <tr>
            <!--college name -->
            <td style="font-weight: bold; font-size:14px">
                <h2>College Name :</h2>
            </td>
            <td><input type="text" size="30" placeholder="College name" style="width:200px;height:30px" /></td>
        </tr>

        <tr>
            <td>
                <h2>Your Department :</h2>
            </td>
            <td>
                <!--for selection of department from user-->
                <select style="width:250px;height:40px">
                    <option value="">Department</option>
                    <option>Computer Science</option>
                    <option>Information Technology</option>
                    <option>Electronics and Communication</option>
                    <option>Electrical </option>
                    <option>Mechanical</option>
                    <option>civil </option>
                    <option>others </option>
                </select>
            </td>
        </tr>
        <tr>
            <!--for course name-->
            <td>
                <h2>Your Course :</h2>
            </td>
            <td><input type="text" size="15" placeholder="Course" style="width:200px;height:30px" />

            </td>
        </tr>
        <!--for current year-->
        <tr>
            <td style="font-weight: bold; font-size:14px">
                <h2>Current Year :</h2>
            </td>
            <td>
                <select>
                    <option value=""> year</option>
                    <option>1st year></option>
                    <option>2nd year></option>
                    <option>3rd year></option>
                    <option>4th year></option>
                    <option>5th year></option>
                    <option>6th year></option>
                </select>
            </td>
        </tr>

        <tr>
            <!--for upload photo-->
            <td>
                <h2>Upload your photo :</h2>
            </td>
            <td><input type="file" style="width:200px;height:30px" /></td>
        </tr>
        <tr>
            <td>
                <h2>Gender</h2>
            </td>
            <!--to select gender-->
            <td>
                <select style="width:200px;height:40px">
                    <option value="">Gender</option>
                    <option>Male</option>
                    <option>Female</option>
                    <option>Other</option>
            </td>
        </tr>
        <tr>
            <!--for mobile number-->
            <td>
                <h2>Mobile number:</h2>
            </td>
            <td> <input type="text" size="1" value="+91" style="width:20px;height:30px" />
                <input type="text" size="10" placeholder="Mobile number" style="width:200px;height:30px" />
            </td>
        </tr>
        <tr>
            <!--for email id-->
            <td>
                <h2> Email id :</h2>
            </td>
            <td><input type="text" size="30" placeholder="Email id" style="width:200px;height:30px" /></td>
        </tr>
        <tr>
            <!--for address-->
            <td>
                <h2>Address :</h2>
            </td>
            <td><input type="text" size="50" placeholder="Address" style="width:200px;height:30px" /></td>
        </tr>
        <tr>
            <!--for submit and reset buttons-->

            <td colspan="2" align="center">
                <input type="submit" value="Submit"
                    style=" width:100px; height:50px;background:linear-gradient(to bottom, #007bff, #0056b3); color: white;" />

                <input type="reset" value="Reset"
                    style=" width:100px; height:50px;background:linear-gradient(to bottom, #dc3545, #c82333); color: white;" />
            </td>
        </tr>


    </table>


</form>

</body>

</html>
