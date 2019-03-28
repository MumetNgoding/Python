# Python
How to use

To install the dependencies for this project, run "pip install -r requirements.txt"
Add a secrets.json file to the root directory of your project. The contents of the file should mirror the following:

{
    "bittrex_key" : "BITTREX_API_KEY",
    "bittrex_secret" : "BITTREX_SECRET",
    "twilio_key": "TWILIO_API_KEY",
    "twilio_secret": "TWILIO_SECRET",
    "twilio_number": "TWILIO_PHONE_NUMBER",
    "my_number": "YOUR_PHONE_NUMBER"
}

If you don't want to use the Twilio notifications, you can remove the code
How to run

Navigate to your file directory in terminal, run with "python app.py"
