1. Use a Local Development Server
Running a local development server will resolve CORS issues. Here’s how you can set one up:

Using Visual Studio Code (VS Code) with Live Server Extension:
Install Live Server Extension:

Open VS Code.
Go to the Extensions view (Ctrl+Shift+X or click the Extensions icon in the sidebar).
Search for "Live Server" and install it.
Open Your Project:

Open your project folder in VS Code.
Run Live Server:

Right-click on your index.html file and select "Open with Live Server" or use the "Go Live" button in the bottom-right corner.
Access Your Site:

This will open your index.html in a browser with a local server, resolving CORS issues.
Using Python (if Python is installed):
Navigate to Your Project Directory:

Open a terminal or command prompt.
Use cd to navigate to the directory containing your index.html.
Start a Simple HTTP Server:

For Python 3.x: Run python -m http.server 8000
For Python 2.x: Run python -m SimpleHTTPServer 8000
Access Your Site:

Open a browser and go to http://localhost:8000.
