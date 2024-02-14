
  # Just another text editor

   ## Table-of-Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
 

  ## Description
  My motivation for this PWA Text Editor project was to create a reliable, browser-based text editor with seamless offline capabilities. I aimed to leverage modern web technologies to ensure data persistence and provide a user-friendly experience akin to native applications, all while enhancing my skills in building progressive web applications that are efficient and practical for everyday use.

  I built this project to delve into Progressive Web Applications (PWA), focusing on offline functionality and data persistence using IndexedDB and service workers. The goal was to create a browser-based text editor that provides a seamless and reliable user experience, even without an internet connection, catering to the needs of developers and writers for accessible and efficient data management.

  This project addresses the need for reliable data access and persistence in a text editor, enabling users to create, save, and retrieve notes or code snippets offline. It solves the issue of potential data loss due to unreliable internet connectivity by utilizing IndexedDB and service workers, thereby enhancing productivity and ensuring seamless work continuity.
 

  ## Installation
  To install the PWA Text Editor project, follow these steps:

1. Clone the Repository:

   Obtain the repository URL and use Git to clone it to your local machine with the command:  
   ```git clone git@github.com:EricRisher/just-another-text-editor.git```
2. Navigate to the Project Directory:

   Change into the project directory using:  
   ```cd main```
3. Install Dependencies:

   Install the required npm packages specified in the package.json file by running:  
   ```npm install```  
4. Start the Application:

   Run the application locally by executing:  

   ```npm run start```  
   This command starts both the backend and serves the client, bundling the JavaScript files using webpack.  

5. Access the Application:

   Open your web browser and go to http://localhost:3000 to use the text editor.  
     

Install the PWA (Optional):  
If supported by your browser, you should see an "Install" icon in the address bar to download and install the web application on your desktop for offline use.

  ## Usage
  To illustrate the usage of the PWA Text Editor after installation, let's walk through a typical user scenario:

Starting the Application  

- After completing the installation steps, you launch the application by navigating to http://localhost:3000 in your web browser. The text editor interface loads, presenting a clean, minimalistic design ready for text input.  

Creating Notes or Code Snippets  

- Input: You start typing your notes or code snippets directly into the text area provided. The interface is intuitive, allowing for straightforward text entry without any distractions.

- Persistence: As you type, the application automatically saves your entries to IndexedDB. If you click off the text editor window (e.g., switch tabs or applications), the content remains saved.

Retrieving Data
- Upon Return: When you reopen the text editor after closing it or even after losing your internet connection, you find that all your previously entered content is intact and displayed exactly as you left it, thanks to the data being retrieved from IndexedDB.  

Offline Functionality
- Working Offline: You test the application's offline capabilities by disabling your internet connection and continuing to use the text editor. The application functions seamlessly, proving its reliability without an active internet connection.  

Installing the Application
- Installation Prompt: At some point, you notice an "Install" button or prompt in the browser. Clicking on it installs the application on your desktop, creating an icon for easy access.

- Launching as a Desktop App: You launch the installed PWA from your desktop, enjoying a standalone experience that feels similar to using a native application, with all the functionalities available offline.

Utilizing Advanced Features  

- Service Worker: The service worker pre-caches your static assets, ensuring that the application loads quickly and reliably each time you open it, enhancing the overall user experience.

  ## Questions
  If you have any questions, please contact me at 
  rishereric13@gmail.com
  or visit my GitHub page at
  [GitHub](https://github.com/ericrisher)

