import React from 'react';
import { Mail, Github, Linkedin, Globe, Phone } from 'lucide-react';

const AboutMe = () => {
  const skills = {
    frontend: ['React.js', 'Next.js', 'Redux', 'Tailwind CSS', 'HTML5/CSS3', 'JavaScript/TypeScript'],
    mobile: ['React Native', 'Mobile UI/UX', 'App Performance Optimization'],
    backend: ['Node.js', 'Express.js', 'MongoDB', 'RESTful APIs'],
    tools: ['Git', 'VS Code', 'Jira', 'Figma']
  };

  return (
    <div className="max-w-4xl mx-auto p-6 space-y-8">
      {/* Header Section */}
      <div className="text-center space-y-4">
        <h1 className="text-4xl font-bold">Fatma Aktas</h1>
        <h2 className="text-2xl text-blue-600">Full Stack Developer</h2>
        <p className="text-gray-600">Specializing in React, React Native, and Full Stack Development</p>
      </div>

      {/* About Section */}
      <div className="bg-white rounded-lg shadow-lg p-6 space-y-6">
        <div className="space-y-4">
          <h3 className="text-xl font-semibold border-b pb-2">About Me</h3>
          <p className="text-gray-700 leading-relaxed">
            Dedicated software developer with expertise in building compelling web and mobile experiences. 
            I specialize in React and React Native development, creating efficient and intuitive user interfaces 
            while maintaining a strong foundation in full-stack development with Node.js and MongoDB.
          </p>
        </div>

        {/* Skills Grid */}
        <div className="grid md:grid-cols-2 gap-6">
          {Object.entries(skills).map(([category, categorySkills]) => (
            <div key={category} className="space-y-2">
              <h4 className="text-lg font-medium capitalize">{category}</h4>
              <div className="flex flex-wrap gap-2">
                {categorySkills.map(skill => (
                  <span 
                    key={skill}
                    className="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                  >
                    {skill}
                  </span>
                ))}
              </div>
            </div>
          ))}
        </div>

        {/* Contact Section */}
        <div className="space-y-4">
          <h3 className="text-xl font-semibold border-b pb-2">Let's Connect</h3>
          <div className="flex flex-wrap gap-4">
            <a 
              href="mailto:faktas2021@gmail.com"
              className="flex items-center gap-2 text-gray-700 hover:text-blue-600 transition-colors"
            >
              <Mail size={20} />
              <span>faktas2021@gmail.com</span>
            </a>
            <div className="flex gap-4">
              <Globe size={20} className="text-gray-700 hover:text-blue-600 cursor-pointer" />
              <Github size={20} className="text-gray-700 hover:text-blue-600 cursor-pointer" />
              <Linkedin size={20} className="text-gray-700 hover:text-blue-600 cursor-pointer" />
            </div>
          </div>
        </div>
      </div>

      {/* Current Focus */}
      <div className="bg-gradient-to-r from-blue-50 to-indigo-50 rounded-lg p-6">
        <h3 className="text-xl font-semibold mb-4">Current Focus</h3>
        <ul className="space-y-2 text-gray-700">
          <li>• Exploring latest frontend and backend technologies</li>
          <li>• Optimizing React Native mobile applications</li>
          <li>• Building scalable full-stack solutions</li>
          <li>• Enhancing UI/UX design skills</li>
        </ul>
      </div>
    </div>
  );
};

export default AboutMe;

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fatmaakts) 
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/_disconnectus?igshid=OGQ5ZDc2ODk2ZA==) 
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/disconnecte_d3) 


# 💻 Tech Stack:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white) ![Angular.js](https://img.shields.io/badge/angular.js-%23E23237.svg?style=for-the-badge&logo=angularjs&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white) ![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) 	![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![GIT](https://img.shields.io/badge/Git-fc6d26?style=for-the-badge&logo=git&logoColor=white) ![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=firefox&logoColor=#FF7139) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white) ![Webflow](https://img.shields.io/badge/Webflow-4353FF?style=for-the-badge&logo=webflow&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=disconnectuss&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=disconnectuss&theme=tokyonight&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=disconnectuss&theme=tokyonight&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=disconnectuss&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=disconnectuss&limit=5&theme=dark&combine_all_yearly_contributions=true)

### 😂 Random Dev Meme
<img src='https://randommeme-five.vercel.app/' style="height: 400px;"/>

---
[![](https://visitcount.itsvg.in/api?id=disconnectuss&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
