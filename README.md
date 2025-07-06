// 💻 Passionate Dev | 📡 Curious IoT Explorer | 🔥 Always Building

const Salman = {
  name: "Salman Faris",
  role: "Full Stack Developer & IoT Explorer",
  techStack: [
    "JavaScript", "TypeScript", "React", "Node.js", "Express",
    "MongoDB", "Firebase", "Tailwind CSS", "EJS", "JWT", "C++"
  ],
  currentlyBuilding: "Cucoon – A smart alert system with real-time siren control and anomaly detection.",
  interests: [
    "Frontend Development 🎨 – building clean, intuitive UIs",
    "Backend Engineering ⚙️ – APIs, DBs, and auth flows",
    "Real-time Applications ⏱️ – fast, reactive, and reliable",
    "IoT Integration 📡 – bringing physical devices into digital workflows",
    "System Design 🧠 – crafting scalable, maintainable architecture",
    "Problem Solving 🔍 – love debugging and logical challenges"
  ],
  askMeAbout() {
    return [
      "Building full-stack web apps using MERN stack 🌐",
      "Designing real-time features using Firebase & WebSockets ⚡",
      "How to integrate microcontrollers with cloud dashboards 📶",
      "Visualizing sensor data in charts & alerts 📊",
      "Creating authentication systems with JWT & Firebase Auth 🔐",
      "UI/UX best practices with Tailwind & React 🖌️"
    ];
  },
  funFact: () =>
    "I once debugged a temperature spike that turned out to be my hand blocking the sensor — now I trust data *and* intuition 😄",
};

console.log(`👋 Hey! I'm ${Salman.name}, a ${Salman.role}`);
console.log("🔎 Interests:");
console.log(Salman.interests.map(i => `- ${i}`).join("\n"));
console.log("💬 Ask me about:");
console.log(Salman.askMeAbout().map(a => `- ${a}`).join("\n"));
console.log(`🚧 Currently building: ${Salman.currentlyBuilding}`);
console.log(`🎉 Fun Fact: ${Salman.funFact()}`);
