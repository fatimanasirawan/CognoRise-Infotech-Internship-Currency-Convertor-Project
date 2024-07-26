1. 𝐔𝐬𝐞 𝐚 𝐋𝐨𝐜𝐚𝐥 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭 𝐒𝐞𝐫𝐯𝐞𝐫
Running a local development server will resolve CORS issues. Here’s how you can set one up:

𝗨𝘀𝗶𝗻𝗴 𝗩𝗶𝘀𝘂𝗮𝗹 𝗦𝘁𝘂𝗱𝗶𝗼 𝗖𝗼𝗱𝗲 (𝗩𝗦 𝗖𝗼𝗱𝗲) 𝘄𝗶𝘁𝗵 𝗟𝗶𝘃𝗲 𝗦𝗲𝗿𝘃𝗲𝗿 𝗘𝘅𝘁𝗲𝗻𝘀𝗶𝗼𝗻:
Install Live Server Extension:

𝐎𝐩𝐞𝐧 𝐕𝐒 𝐂𝐨𝐝𝐞.
Go to the Extensions view (Ctrl+Shift+X or click the Extensions icon in the sidebar).
Search for "Live Server" and install it.

𝐎𝐩𝐞𝐧 𝐘𝐨𝐮𝐫 𝐏𝐫𝐨𝐣𝐞𝐜𝐭:
Open your project folder in VS Code.

𝐑𝐮𝐧 𝐋𝐢𝐯𝐞 𝐒𝐞𝐫𝐯𝐞𝐫:
Right-click on your index.html file and select "Open with Live Server" or use the "Go Live" button in the bottom-right corner.

𝐀𝐜𝐜𝐞𝐬𝐬 𝐘𝐨𝐮𝐫 𝐒𝐢𝐭𝐞:
This will open your index.html in a browser with a local server, resolving CORS issues.

𝐔𝐬𝐢𝐧𝐠 𝐏𝐲𝐭𝐡𝐨𝐧 (𝐢𝐟 𝐏𝐲𝐭𝐡𝐨𝐧 𝐢𝐬 𝐢𝐧𝐬𝐭𝐚𝐥𝐥𝐞𝐝):
Navigate to Your Project Directory:
Open a terminal or command prompt.
Use cd to navigate to the directory containing your index.html.

𝐒𝐭𝐚𝐫𝐭 𝐚 𝐒𝐢𝐦𝐩𝐥𝐞 𝐇𝐓𝐓𝐏 𝐒𝐞𝐫𝐯𝐞𝐫:
For Python 3.x: Run python -m http.server 8000
For Python 2.x: Run python -m SimpleHTTPServer 8000

𝐀𝐜𝐜𝐞𝐬𝐬 𝐘𝐨𝐮𝐫 𝐒𝐢𝐭𝐞:
Open a browser and go to http://localhost:8000.
