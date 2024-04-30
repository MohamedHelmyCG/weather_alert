Weather Forecast Notification

This script retrieves weather forecast data from the OpenWeatherMap API and sends a notification via Twilio if it's going to rain.

Overview

This script checks the weather forecast for your specified location and sends a notification if rain is predicted within the next few hours.

Prerequisites

Before running the script, make sure you have the following:

- Python installed on your machine
- Access to the OpenWeatherMap API (sign up at https://openweathermap.org/ to obtain an API key)
- Twilio account (sign up at https://www.twilio.com/ to obtain Account SID, Auth Token, and a Twilio phone number)

Installation

1. Clone this repository to your local machine:

   git clone https://github.com/MohamedHelmyCG/weather-forecast-notification.git

2. Install the required Python packages:

pip install -r requirements.txt


Usage

1. Set up environment variables:

- Set the OWM_API_KEY environment variable to your OpenWeatherMap API key.
- Set the AUTH_TOKEN environment variable to your Twilio Auth Token.
- Optionally, set up a proxy if required, using the https_proxy environment variable.

2. Configure the script:

- Replace "YOUR ACCOUNT SID" with your Twilio Account SID.
- Replace "YOUR TWILIO VIRTUAL NUMBER" with your Twilio virtual phone number.
- Replace "YOUR TWILIO VERIFIED REAL NUMBER" with your verified real phone number.

3. Run the script:

main.py 


Important Notes

- Make sure to obtain necessary API keys and tokens before running the script.
- Ensure that your Twilio virtual number is configured to send messages to your verified real number.
- Adjust the weather parameters (latitude, longitude) according to your location.

Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.


