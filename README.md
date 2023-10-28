

Project Description:
This project is a web application built using React and a variety of popular libraries and technologies. It combines the power of React with Material UI for a sleek user interface, React-Redux for state management, ReactAvatar-edit for avatar customization, React-Router-Dom for navigation, and more.



## Introduction
* Resume-builder is a web application where anyone can create resume with ease and choose from different available templates.
* It has three tabs : 1) Resume Templates (Home Page) , 2) My Resume, 3) About us
* Before downloading we have a preview option to view your resume.
* You can download resumes to the local hard drive.


Features:
* React-Router-Dom: Efficient and dynamic routing for the application. <br/>
* Material UI: A modern and responsive user interface using Material Design components. <br/>
* React-Redux: Centralized state management for easy data sharing and updates. <br/>
* ReactAvatar-edit: Customize avatars for user profiles. <br/>
* Vanilla CSS: Custom styles to tailor the user interface to your preferences. <br/>
* JSX: JavaScript XML for creating UI components. <br/>
* React-Hook-Forms: Simplify form handling using hooks in React. <br/>
* Jspdf Converter: Generate PDF files directly from your web application. <br/>
* Redux: Manage and share state globally across your application. <br/>
* Images: Utilize images in various parts of the application for a rich visual experience. <br/>

Installation
1.Clone the repository:<br/>
git clone https://github.com/yourusername/your-project.git<br/>
2.Change directory to the project folder:<br/>
cd your-project<br/>
3.Install the required dependencies:<br/>
npm install<br/>
4.Start the development server:<br/>
npm start<br/>
5.Access the application in your browser at http://localhost:3000.<br/>

## Pages
* Home (Resume Templates) -Choose one from the available templates ;
 <br/> -Navigated to details filling page
* My Resume - From where you can see your resume before downloading 
* About us

Contributing:<br/>
If you would like to contribute to this project, please follow these steps:<br/>

1.Fork the repository.<br/>
2.Create a new branch for your feature or bug fix:<br/>
git checkout -b feature-name<br/>
3.Commit your changes and push to your fork:<br/>
git commit -m "Add feature or fix"<br/>
git push origin feature-name<br/>
4.Create a pull request on the original repository.<br/>

Contact<br/>
If you have any questions or need further assistance, please contact [gulamquadir500@gmail.com].<br/>

Enjoy working with this React project, and feel free to customize it to your specific needs! We welcome your contributions and hope it serves as a valuable resource for your web development endeavors.<br/>

Project Structure:
# Resume-Builder (AlmaBetter__Capstone__Project)

├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
│
├── src/
│   ├── App.js
│   ├── index.css
│   ├── index.js
│   │
│   └── Components/
│       ├── about_us_page/
│       │   └── aboutus.jsx
│       │
│       ├── detail_filling_page/
│       │   ├── navtabs/
│       │   │   └── navtabs.jsx
│       │   ├── detail.jsx
│       │   ├── education.jsx
│       │   ├── keyskills.jsx
│       │   ├── personal_info.jsx
│       │   └── workexperience.jsx
│       │
│       ├── homepage/
│       │   ├── my_templates.jsx
│       │   ├── mytamplate.css
│       │   ├── template1.jsx
│       │   ├── template2.jsx
│       │   ├── template3.jsx
│       │   └── template4.jsx
│       │
│       ├── preview_page/
│       │   ├── preview.jsx
│       │   └── preview.css
│       │
│       ├── images/
│       │   ├── aboutCv.jpg
│       │   ├── T1.png
│       │   ├── T2.png
│       │   ├── T3.png
│       │   └── T4.png
│       │
│       ├── navbar/
│       │   └── navbar.jsx
│       │
│       ├── PersonalInfo/
│       │   ├── PersonalInfoComponent.css
│       │   └── PersonalInfoComponent.js
│       │
│       └── Preview/
│           ├── PreviewComponent.css
│           └── PreviewComponent.js
│
├── constant/
│   └── actiontype.js
│
├── state/
│   ├── action/
│   ├── action.js
│   ├── index.js
│   └── Sel_Template.js
│
├── reducer/
│   ├── index.js
│   ├── Sel_Template.js
│   └── updateinforeducer.js
│
└── store/
    └── store.js
