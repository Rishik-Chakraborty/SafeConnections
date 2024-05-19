<!DOCTYPE html>
<html>
<head>
    <title>SafeConnections</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 20px;">
    <h1 style="font-size: 2em; color: #333;">SafeConnections</h1>

    <h2 style="font-size: 1.5em; color: #444;">Technical Background</h2>
    <p>SafeConnections is an innovative project developed for Wilfrid Laurier University's Hackathon, HawkHacks, by Rishik Chakraborty, Kavir Auluck, and Devansh Goel, from May 17-19. This project, which has been deployed on GitHub Pages, demonstrates our commitment to leveraging technology for social good. To get it running, follow the deployment link or download the source files to use as a template. Note that this project cannot be used directly for any sort of assessment, hackathon, and similar events.</p>

    <h2 style="font-size: 1.5em; color: #444;">Prerequisites</h2>
    <p>To run the backend of the project, you will need a Python code editor (preferably PyCharm) and a text editor such as VS Code. These tools will allow you to interact with and modify the code effectively.</p>

    <h2 style="font-size: 1.5em; color: #444;">Installation</h2>
    <p>Downloading and setting up the code is straightforward. Download the zip files and open them in the respective applications, or follow GitHub's guidelines to clone the repository.</p>

    <h2 style="font-size: 1.5em; color: #444;">Project Necessity</h2>
    <p>Our target demographic is Southern African countries, where the rate of trafficking is the highest in the world. In 2021, an estimated 7 million Africans were in modern slavery (5.2 per thousand people), with 3.8 million children in forced labor, and 72% of crimes being coordinated online. Our solution aims to reduce the number of children trafficked by providing a more secure platform. Using a low level of unsupervised machine learning, we notify parents of suspected trafficking attempts. We hope our messaging platform, if implemented, will significantly reduce online crimes and increase children's safety online.</p>

    <h2 style="font-size: 1.5em; color: #444;">Technical Details</h2>
    <p>This project integrates several languages for functional use, including HTML, CSS, Java, React.js, Node.js, Apps Script, and Python. Figma was used to assist in the user-facing front-end code.</p>
    <p>Google Sheets is used as an intermediary to connect the front-end code to the Python backend. The following libraries/APIs were used:</p>
    <ul style="list-style-type: disc; margin-left: 20px;">
        <li>pandas as pd</li>
        <li>TfidfVectorizer from sklearn.feature_extraction.text</li>
        <li>joblib</li>
        <li>ServiceAccountCredentials from oauth2client.service_account</li>
        <li>gsheets</li>
        <li>Client from twilio.rest</li>
    </ul>
    <p>CSV files were used throughout the code to interpret data.</p>
</body>
</html>
