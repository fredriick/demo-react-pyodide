Below are some files you might need to modify for your own project:

🐍 src/python/script.py
This file contains a toy Python function being defined and run inside your browser using pyodide. You can modify this to have more complex use cases (e.g. load standard libraries, pandas, numpy, etc.). For more details, read the pyodide docs.

⚛️ src/App.js
This file contains the code that reads a python script, load pyodide and run the script. It also renders a basic React app directly derived from create-react-app, which can be easily modified. You will need to modify this file if you want to access the Python scope from JS or load packages like numpy, pandas, etc.

📇 public/index.html
The code in the html template was modified to load pyodide inside the <head>. If you wish to change the version of pyodide being loaded, you will have to modify the loading.

🎨 src/App.css
Modify this file or index.css in order to add custom styling to your application.

🧪 src/App.test.js
No test has been set up for this project. You will need to create your own tests and run them with npm run test.

Here
https://fredriick.github.io/demo-react-pyodide/

