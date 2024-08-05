<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
    <link rel="stylesheet" href="../node_modules/bootstrap-icons/font/bootstrap-icons.css">
    <style>
        .gold{
            background-color: gold;
            border-radius: 180px;
            color: black;
            display: inline-block;
            padding: 5px;
            align-content: center;
        }
        .silver{
            background-color: silver;
            color: black;
            border-radius: 180px;
            display: inline-block;
            padding: 5px;
        }
        .bronze{
            background-color: burlywood;
            color: black;
            border-radius: 180px;
            display: inline-block;
            padding: 5px;
        }
        .g{
            background-color: gold;
            width: 10px;
            height: 10px;
            border-radius: 180px;
            display: inline-block;
        }
        .s{
            background-color: silver;
            width: 10px;
            height: 10px;
            border-radius: 180px;
            display: inline-block;
        }
        .b{
            background-color: burlywood;
            width: 10px;
            height: 10px;
            border-radius: 180px;
            display: inline-block;
        }
       table{
            align-items: center;
            background-color: beige;
            font-family:Arial, Helvetica, sans-serif;
        }
        tr{
            box-shadow: 2px 2px 2px 2px;
        }
        .heading{
            font-family: Arial, Helvetica, sans-serif;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <table border="0" width="100%" height="100px" cellpadding="5px" align="center" cellspacing="5px">
        <caption class="heading">OLYMPIC-2024</caption> 
        <colgroup span="2"></colgroup>  
        <thread >
            <tr align="center">
            <th>no</th>
            <th align="left">country</th>
            <th><span class="gold">G</span></th>
            <th><span class="silver">S</span></th>
            <th><span class="bronze">B</span></th>
            <th><span class="g"></span> <span class="s"></span><br> <span class="b"></span></th>
            <th>&nbsp;</th>
            </tr>
        </thread> 
        <tbody>
            <tr align="center">
                <td>1</td>
                <td align="left"><span><img src="./images/america.JPG" width="10%">America</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
            <tr align="center">
                <td>2</td>
                <td align="left"><span><img src="./images/china.JPG" width="10%">China</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
            <tr align="center">
                <td>3</td>
                <td align="left"><span><img src="./images/australia.JPG" width="10%">Australia</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
            <tr align="center">
                <td>4</td>
                <td align="left"><span><img src="./images/britain.JPG" width="10%">britain</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
            <tr align="center">
                <td>5</td>
                <td align="left"><span><img src="./images/france.JPG" width="10%">France</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
            <tr align="center">
                <td>6</td>
                <td align="left"><span><img src="./images/italy.JPG" width="10%">Italy</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
            <tr align="center">
                <td>7</td>
                <td align="left"><span><img src="./images/japan.JPG" width="10%">Japan</span></td>
                <td>13</td>
                <td>14</td>
                <td>15</td>
                <td>42</td>
                <td class="bi bi-plus-square"></td>
            </tr>
        </tbody>
        <tfoot>
            <tr  valign="center">
                <td colspan="7">
                     Last updated:August 5, 2024 at 09:44 (your local time)
                    <br>
                    Does not include medals won by AIN.
                </td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
