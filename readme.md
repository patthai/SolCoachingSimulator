# School of Leadership - Coaching Simulator Tools

A collection of interactive web-based coaching tools designed to facilitate leadership development through guided reflection, structured coaching frameworks, and mentor-mentee interactions.

## 🌟 Overview

The School of Leadership Coaching Simulator Tools provide an immersive learning experience for leadership development through three integrated applications:

1. **T-GROW Coaching Platform** - A step-by-step guided coaching experience using the T-GROW framework
2. **Enhanced T-GROW Coaching Platform** - An alternative version with enhanced animations and user experience
3. **Mentor Question Refiner** - A tool to help users craft more effective questions for mentorship

These tools leverage AI-powered feedback to simulate real coaching conversations and guide users through structured reflection processes.

## 🛠️ Tools Included

### 1. T-GROW Coaching Platform (index_2.html)

A comprehensive coaching platform built around the T-GROW framework:
- **T**opic - Define the coaching conversation topic
- **G**oal - Establish clear, measurable objectives
- **R**eality - Assess the current situation
- **O**ptions - Explore available choices
- **W**ill - Create an action plan

Features:
- Progressive step-by-step interface
- AI-powered feedback at each stage
- Simulated coaching conversation
- Guided reflection process
- Action plan development

### 2. Enhanced T-GROW Platform (index.html)

An upgraded version of the T-GROW platform with:
- Improved UI/UX with animated elements
- Card-based interaction system
- More conversational AI integration
- Enhanced visual feedback
- More intuitive navigation

### 3. Mentor Question Refiner (index_3.html)

A specialized tool to improve the quality of questions asked during mentorship:
- Four-step refinement process: Draft, Reflect, Simulate, Refine
- AI-guided reflection on question quality
- Simulation of mentor responses
- Iterative improvement process
- Final question comparison

## 💻 Installation & Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/school-of-leadership-tools.git
   ```

2. **API Configuration**:
   - These tools require an OpenAI API key
   - Replace the placeholder `'[X]'` in the code with your actual API key
   - In each HTML file, look for:
     ```javascript
     headers: {
       'Content-Type': 'application/json',
       'Authorization': '[X]'
     }
     ```

3. **Deployment Options**:
   - Host on any web server or static hosting service
   - Can be used locally by opening the HTML files in a browser
   - For production, consider secure storage of API keys

## 🚀 Usage

### T-GROW Coaching Tool
1. Open `index.html` or `index_2.html` in a web browser
2. Enter your topic for coaching
3. Define your goal for the session
4. Describe your current reality/situation
5. Explore options available to you
6. Commit to a plan of action
7. Engage with the virtual coach
8. Reflect on the process and learnings

### Mentor Question Refiner
1. Open `index_3.html` in a web browser
2. Draft your initial question
3. Review AI-guided reflection on your question
4. See a simulation of how a mentor might respond
5. Refine your question for better clarity and effectiveness

## 🔧 Technologies Used

- HTML5
- CSS3 (with Tailwind CSS)
- JavaScript (ES6+)
- OpenAI API
- Animations using CSS transitions and keyframes
- Web fonts (Google Fonts - Sarabun, Prompt)
- LocalStorage for state management

## 📄 License

MIT License

## 🙏 Acknowledgments

- T-GROW coaching framework
- Tailwind CSS for styling
- OpenAI for AI-powered feedback
- Google Fonts for typography

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](link-to-issues) if you want to contribute.
