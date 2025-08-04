<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Gabriel%20Baldassari&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&width=800&height=100&lines=🚀+Full+Stack+Developer;💻+React+%7C+Next.js+%7C+TypeScript+Expert;🌟+Building+Amazing+Digital+Experiences;🎯+Always+Learning+%26+Growing" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="500">
</div>

## 🎭 Who Am I?

<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

```javascript
class Developer {
  constructor() {
    this.name = "Gabriel Baldassari";
    this.role = "Senior Full Stack Developer";
    this.location = "São Paulo, Brazil 🇧🇷";
    this.experience = "4+ years";
    this.passion = "Creating digital solutions that matter";
    this.motto = "Code with purpose, build with passion";
  }

  getCurrentStatus() {
    return {
      learning: ["Next.js 14", "AI Integration", "Microservices"],
      working: "E-commerce Platform with 50k+ users",
      collaborating: "Open Source React Components Library",
      challenge: "Building scalable systems that grow with business"
    };
  }

  getSkillLevel(skill) {
    const skills = {
      "React/Next.js": "⭐⭐⭐⭐⭐",
      "TypeScript": "⭐⭐⭐⭐⭐",
      "Node.js": "⭐⭐⭐⭐⭐",
      "Python": "⭐⭐⭐⭐",
      "AWS": "⭐⭐⭐⭐",
      "Docker": "⭐⭐⭐⭐"
    };
    return skills[skill] || "Learning...";
  }
}

const gabriel = new Developer();
console.log(gabriel.getCurrentStatus());
