<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rewards Redemption Site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        .container {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            width: 100%;
            max-width: 400px;
        }
        h1 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .user-info {
            margin-bottom: 20px;
            text-align: right;
        }
        .user-info span {
            display: block;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-group button {
            width: 100%;
            padding: 10px;
            background: #007BFF;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .form-group button:hover {
            background: #0056b3;
        }
        .notice {
            margin-top: 20px;
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .notice h2 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .notice ul {
            padding-left: 20px;
        }
        .notice ul li {
            margin-bottom: 5px;
        }
        .footer {
            margin-top: 20px;
            font-size: 0.8em;
            color: #777;
            text-align: center;
        }
    </style>
</head>
<body>

        <span>Hello, hi</span>
<div class="container">
    <div class="user-info">
        <span>(Region: IND)</span>
        <span><a href="#">Log Out</a></span>
    </div>
    <h1>Redeem your code</h1>
    <form id="redeemForm">
        <div class="form-group">
            <input type="text" id="redeemCode" placeholder="Enter redemption code" required>
        </div>
        <div class="form-group">
            <button type="submit">Confirm</button>
        </div>
    </form>
    <div class="notice">
        <h2>Important Notice:</h2>
        <ul>
            <li>Redemption code has 12/16 characters, consisting of capital letters and numbers.</li>
            <li>Item rewards are shown in [vault] tab in game lobby; Golds or diamonds will add in account wallet automatically.</li>
            <li>Please note redemption expiration date. Any expired codes cannot be redeemed.</li>
            <li>Please contact customer service if you encounter any issues.</li>
            <li>Reminder: you will not be able to redeem your rewards with guest accounts. You may bind your account to Facebook or VK in order to receive the rewards.</li>
        </ul>
    </div>
</div>

<div class="footer">
    Copyright © Garena International.<br>
    Trademarks belong to their respective owners. All rights reserved.
</div>

<script>
    document.getElementById('redeemForm').addEventListener('submit', function(event) {
        event.preventDefault();
        const code = document.getElementById('redeemCode').value;
        alert(`Redeem code submitted: ${code}`);
    });
</script>

</body>
</html>
