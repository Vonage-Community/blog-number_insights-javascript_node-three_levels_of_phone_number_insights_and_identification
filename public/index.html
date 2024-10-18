<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phone Number Lookup</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .response-box {
            border: 1px solid #ccc;
            padding: 10px;
            margin-top: 10px;
            height: 600px; 
            overflow-y: auto;
            white-space: pre-wrap; 
        }
        .basic-response {
            background-color: #ffe5b4;
        }
        .standard-response {
            background-color: #e9f7ef; 
        }
        .advanced-response {
            background-color: #fce4ec; 
        }
        .center-button {
            display: flex;
            justify-content: center;
        }
        .center-title {
            text-align: center;
        }
        .center-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .form-control {
            width: 100%; 
            height: calc(1.5em + .75rem + 2px); 
            text-align: center;
        }
        .btn-basic {
            background-color: #ffcc80; 
            border-color: #ffcc80;
        }
        .btn-standard {
            background-color: #c8e6c9; 
            border-color: #c8e6c9;
        }
        .btn-advanced {
            background-color: #f8bbd0; 
            border-color: #f8bbd0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="mt-5 center-title">Phone Number Lookup</h1>
        <form id="lookupForm" class="mt-3 center-form">
            <div class="form-group">
                <input type="text" class="form-control" id="phoneNumber" placeholder="Enter phone number" required>
            </div>
            <div class="center-button">
                <button type="button" class="btn btn-primary" onclick="performLookup('all')">ALL Lookups</button>
            </div>
        </form>
        <div class="row mt-5">
            <div class="col-md-4">
                <h3 class="center-title">Basic Lookup</h3>
                <div id="basicResponse" class="response-box basic-response"></div>
                </br>
                <div class="center-button">
                    <button type="button" class="btn btn-basic" onclick="performLookup('basic')">Basic Lookup</button>
                </div>
            </div>
            <div class="col-md-4">
                <h3 class="center-title">Standard Lookup</h3>
                <div id="standardResponse" class="response-box standard-response"></div>
                </br>
                <div class="center-button">
                    <button type="button" class="btn btn-standard" onclick="performLookup('standard')">Standard Lookup</button>
                </div>
            </div>
            <div class="col-md-4">
                <h3 class="center-title">Advanced Lookup</h3>
                <div id="advancedResponse" class="response-box advanced-response"></div>
                </br>
                <div class="center-button">
                    <button type="button" class="btn btn-advanced" onclick="performLookup('advanced')">Advanced Lookup</button>
                </div>
            </div>
        </div>
    </div>
    <script>
        function isValidPhoneNumber(phoneNumber) {
            // Regular expression for validating E.164 phone numbers
            const phoneRegex = /^\+?[1-9]\d{1,14}$/;
            return phoneRegex.test(phoneNumber);
        }

        async function performLookup(type) {
            const phoneNumber = document.getElementById('phoneNumber').value;

            if (!phoneNumber) {
                alert('Please enter a phone number');
                return;
            }

            if (!isValidPhoneNumber(phoneNumber)) {
                alert('Please enter a valid phone number in E.164 format');
                return;
            }

            try {
                if (type === 'all' || type === 'basic') {
                    const basicResponse = await fetch(`/lookup?phonenumber=${phoneNumber}&type=basic`);
                    const basicData = await basicResponse.json();
                    document.getElementById('basicResponse').innerText = JSON.stringify(basicData, null, 2);
                }

                if (type === 'all' || type === 'standard') {
                    const standardResponse = await fetch(`/lookup?phonenumber=${phoneNumber}&type=standard`);
                    const standardData = await standardResponse.json();
                    document.getElementById('standardResponse').innerText = JSON.stringify(standardData, null, 2);
                }

                if (type === 'all' || type === 'advanced') {
                    const advancedResponse = await fetch(`/lookup?phonenumber=${phoneNumber}&type=advanced`);
                    const advancedData = await advancedResponse.json();
                    document.getElementById('advancedResponse').innerText = JSON.stringify(advancedData, null, 2);
                }
            } catch (error) {
                console.error('Error performing lookup:', error);
                alert('Error performing lookup. Please check the console for details.');
            }
        }
    </script>
</body>
</html>
