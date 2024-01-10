

# Project Description:
This project is a web application built using React and a variety of popular libraries and technologies. It combines the power of React with Material UI for a sleek user interface, React-Redux for state management, ReactAvatar-edit for avatar customization, React-Router-Dom for navigation, and more.



# Introduction
* Resume-builder is a web application where anyone can create resume with ease and choose from different available templates.
* It has three tabs : 1) Resume Templates (Home Page) , 2) My Resume, 3) About us
* Before downloading we have a preview option to view your resume.
* You can download resumes to the local hard drive.


# Features:
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

# Installation:
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

# Contributing:
If you would like to contribute to this project, please follow these steps:<br/>

1.Fork the repository.<br/>
2.Create a new branch for your feature or bug fix:<br/>
git checkout -b feature-name<br/>
3.Commit your changes and push to your fork:<br/>
git commit -m "Add feature or fix"<br/>
git push origin feature-name<br/>
4.Create a pull request on the original repository.<br/>

# Contact
If you have any questions or need further assistance, please contact [gulamquadir500@gmail.com].<br/>

Enjoy working with this React project, and feel free to customize it to your specific needs! We welcome your contributions and hope it serves as a valuable resource for your web development endeavors.<br/>

# Live Project Link
https://resume-builder002.netlify.app/
<br/>

# Project Structure:
# Resume-Builder (AlmaBetter__Capstone__Project)

├── public/<br/>
│   ├── favicon.ico<br/>
│   ├── index.html<br/>
│   ├── logo192.png<br/>
│   ├── logo512.png<br/>
│   ├── manifest.json<br/>
│   └── robots.txt<br/>
│<br/>
├── src/<br/>
│   ├── App.js<br/>
│   ├── index.css<br/>
│   ├── index.js<br/>
│   │<br/>
│   └── Components/<br/>
│       ├── about_us_page/<br/>
│       │   └── aboutus.jsx<br/>
│       │<br/>
│       ├── detail_filling_page/<br/>
│       │   ├── navtabs/<br/>
│       │   │   └── navtabs.jsx<br/>
│       │   ├── detail.jsx<br/>
│       │   ├── education.jsx<br/>
│       │   ├── keyskills.jsx<br/>
│       │   ├── personal_info.jsx<br/>
│       │   └── workexperience.jsx<br/>
│       │<br/>
│       ├── homepage/<br/>
│       │   ├── my_templates.jsx<br/>
│       │   ├── mytamplate.css<br/>
│       │   ├── template1.jsx<br/>
│       │   ├── template2.jsx<br/>
│       │   ├── template3.jsx<br/>
│       │   └── template4.jsx<br/>
│       │<br/>
│       ├── preview_page/<br/>
│       │   ├── preview.jsx<br/>
│       │   └── preview.css<br/>
│       │<br/>
│       ├── images/<br/>
│       │   ├── aboutCv.jpg<br/>
│       │   ├── T1.png<br/>
│       │   ├── T2.png<br/>
│       │   ├── T3.png<br/>
│       │   └── T4.png<br/>
│       │<br/>
│       ├── navbar/<br/>
│       │   └── navbar.jsx<br/>
│       │<br/>
│       ├── PersonalInfo/<br/>
│       │   ├── PersonalInfoComponent.css<br/>
│       │   └── PersonalInfoComponent.js<br/>
│       │<br/>
│       └── Preview/<br/>
│           ├── PreviewComponent.css<br/>
│           └── PreviewComponent.js<br/>
│<br/>
├── constant/<br/>
│   └── actiontype.js<br/>
│<br/>
├── state/<br/>
│   ├── action/<br/>
│   ├── action.js<br/>
│   ├── index.js<br/>
│   └── Sel_Template.js<br/>
│<br/>
├── reducer/<br/>
│   ├── index.js<br/>
│   ├── Sel_Template.js<br/>
│   └── updateinforeducer.js<br/>
│<br/>
└── store/<br/>
    └── store.js<br/>
