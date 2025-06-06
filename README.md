**My Portfolio**

**Overview:**


Welcome to my personal portfolio! This project showcases my skills, projects, and contact information as a web developer, designer, and problem solver. Built with modern web technologies, it features a responsive design, dark/light theme toggle, and an interactive chat feature to engage visitors.

**Website:**
Visit the live site: https://omportfolio-x.web.app/


**Features:**

Responsive Design: Adapts seamlessly to desktop, tablet, and mobile devices.
Theme Toggle: Switch between light and dark modes, with preferences saved in local storage.
Smooth Scrolling: Navigate sections (Home, About, Skills, Projects, Contact) with ease.
Interactive Chat: Ask questions about me via a chat bubble, with a typing indicator for a dynamic feel.
Project Showcase: Displays key projects like ShopSphere, TaskSync, and BlogVibe with hover effects.
Contact Form: Simple form to send messages (with basic validation via JavaScript).

**Technologies Used:**

HTML5: Structure of the webpage.
CSS3 & Tailwind CSS: Styling with custom variables, animations, and responsive layouts via Tailwind CDN (v2.2.19).
JavaScript: Handles theme toggle, smooth scrolling, contact form submission, and chat functionality.
Firebase: Initialized for analytics (configuration included, replace API_KEY with your own).

**Setup Instructions:**

Clone the Repository:git clone https://github.com/your-username/om-kumar-portfolio.git


**Open the Project:**
Navigate to the project folder.
Open index.html in a web browser to view the portfolio locally.


**Firebase Configuration:**
Replace "API_KEY" in the <script> section with your actual Firebase API key.
Ensure you have a Firebase project set up at Firebase Console.


**Chat Functionality:**
The chat feature uses the Gemini API for responses. Replace "YOUR_ACTUAL_API_KEY" in the sendMessage() function with your valid Gemini API key.
Note: Without a valid API key, the chat will display a fallback error message.



**File Structure:**

index.html: Main file containing the portfolio structure, styles, and scripts.
External assets:
Images for profile and projects (hosted on i.ibb.co and other CDNs).
Tailwind CSS via CDN.
Firebase SDK via CDN for analytics.



**Usage:**

Navigation: Click links in the fixed navbar to jump to sections.
Theme Toggle: Click the sun/moon icon to switch themes.
Chat: Click the "Ask Anything About Me" bubble, type a message, and press Enter or click Send.
Contact: Fill out the form and click "Send Message" for a simple alert-based submission.

**Customization:**

Update the profile image in the About and Chat sections with your own (replace i.ibb.co URLs).
Modify project details (images, titles, descriptions, links) in the Projects section.
Adjust colors and styles in the :root and .dark CSS variables.
Enhance the chat response logic by refining the prompt in the sendMessage() function.

**Notes:**

API Keys: Ensure Firebase and Gemini API keys are secure and not exposed in public repositories.
Images: External image URLs are used; host your own for better reliability.
Browser Compatibility: Tested on modern browsers (Chrome, Firefox, Edge).

**License**


**© 2025 Om Kumar. All rights reserved.**


**Contact**


Feel free to reach out via the contact form or connect with me on GitHub: iamomm-hack
