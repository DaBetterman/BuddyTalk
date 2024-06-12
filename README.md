# **BuddyTalk**

---

## **Introduction**

Welcome to **BuddyTalk**, your voice-activated virtual assistant for managing Google Calendar events! This project leverages voice commands to help you effortlessly create, read, update, and delete calendar events. BuddyTalk was developed with the goal of providing a hands-free way to handle scheduling tasks, making it a perfect tool for busy individuals who need quick and efficient calendar management.

- **Deployed Project:** [BuddyTalk](https://your-deployed-project-link)
- **Project Blog Article:** [Read the Full Story](https://medium.com/@1ebrahimr/creating-buddytalk-my-journey-with-a-virtual-assistant-befc0ebe62c0)
- **Author:** Ebrahim Rhode
  - [LinkedIn](https://www.linkedin.com/in/ebrahim-rhode/)
  - [GitHub](https://github.com/DaBetterman/portfolio_project)

---

## **Installation**

To get **BuddyTalk** up and running locally on your machine, follow these steps:

1. **Clone the Repository**
   ```
   git clone https://github.com/DaBetterman/portfolio_project.git
   cd BuddyTalk
   ```

2. **Set Up a Virtual Environment**

```
python3 -m venv venv
source venv/bin/activate
```

3. **Install the Required Dependencies**

```
pip install -r requirements.txt
```

4. **Set Up Google Calendar API**


Go to the `Google Cloud Console`.
Create a new project and enable the `Google Calendar API`.
Generate OAuth 2.0 credentials and download the `credentials.json` file.
Place the credentials.json file in the root directory of your project.
Run the Application.

```
flask run
```

# **Usage**

Once you have BuddyTalk running, you can access it at `http://localhost:5000` (or your deployed URL). Here's how to use it:

1. **Access the Landing Page**

Visit the landing page where you can see an overview of what BuddyTalk can do.
2. **Login with Google**

Authenticate with your Google account to allow BuddyTalk to access your calendar.
3. **Use Voice Commands**

Navigate to the dashboard where you can use voice commands to manage your Google Calendar events. Simply speak commands like "Create an event," "List my events," or "Delete an event."

# **Contributing**
We welcome contributions to improve **BuddyTalk!** Here’s how you can get involved:

1. **Fork the Repository**

Click the “Fork” button at the top right of the repository page.

2. **Create a Branch**

```
git checkout -b feature/your-feature-name
```

3. **Make Your Changes**

Implement your changes and commit them with clear, concise messages.

4. **Push Your Changes**

```
git push origin feature/your-feature-name
```

5. **Submit a Pull Request**

Go to the repository’s GitHub page and click the “Pull Request” button.


# **Licensing**

BuddyTalk is licensed under the MIT License. You can view the full license in the LICENSE file.

# **Project Inspiration and Technical Challenges**

**Inspiration**

**BuddyTalk** was inspired by my desire to create a personal assistant that simplifies the way we interact with our schedules. I’ve always been intrigued by how technology can enhance our daily lives, and BuddyTalk is a step towards realizing that potential. The decision to include voice commands came from my own experience of juggling multiple tasks and needing a more efficient way to manage my time.

**Technical Challenges**

One of the most significant challenges I faced was implementing a voice selection feature on a Linux/Ubuntu system. Given the limited text-to-speech (TTS) options available, I had to explore various libraries and cloud-based solutions. I ultimately opted for a basic TTS setup that works within the constraints of the operating system. This experience highlighted the importance of flexibility and creative problem-solving in development.

**Future Enhancements**

Looking ahead, I’m excited to expand BuddyTalk’s capabilities. Planned features include integrating a weather API to provide weather updates and adding Google Maps functionality for navigating and planning routes—all controlled by voice commands. These enhancements will make BuddyTalk an even more versatile and powerful assistant.

**About the Author**

I'm **Ebrahim Rhode**, a passionate software developer committed to continuous learning and innovation. I thrive on solving complex problems and bringing creative ideas to life through code. You can learn more about my work and connect with me on [LinkedIn](https://www.linkedin.com/in/ebrahim-rhode/)

Thank you for exploring BuddyTalk! If you have any questions or suggestions, feel free to reach out or contribute to the project.
