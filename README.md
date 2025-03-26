# 💬 WhatsApp-Style Real-Time Chat Application

## 🚀 Overview

This is a full-stack real-time chat application built using ASP.NET Core SignalR for the backend and HTML/JavaScript for the frontend. The application supports both private and group messaging with a WhatsApp-inspired design.

## ✨ Features

- 💬 Private Messaging
- 👥 Group Chat Functionality
- 🎨 Responsive and Modern UI
- 🔄 Real-Time Message Delivery
- 📱 WhatsApp-Like Design

## 🛠 Technologies Used

- **Backend:**
  - ASP.NET Core
  - SignalR
- **Frontend:**
  - HTML5
  - JavaScript
  - Tailwind CSS
  - Font Awesome

## 📦 Prerequisites

- .NET 6.0 or later
- Visual Studio 2022 (recommended)
- Modern web browser

## 🔧 Installation

### Backend Setup

1. Clone the repository

```bash
git clone https://github.com/ManthanThakor/ChatApp.git
cd ChatApp
```

2. Open the solution in Visual Studio
3. Restore NuGet packages
4. Configure SignalR in `Startup.cs` or `Program.cs`

### Frontend Setup

- No additional setup required
- Ensure SignalR backend is running at `https://localhost:7141/chatHub`

## 🚦 Running the Application

1. Start the ASP.NET Core backend
2. Open the HTML file in a web browser
3. Enter your username to join the chat

## 🌟 How to Use

1. Enter a unique username
2. Choose between Private or Group Chat mode
3. Send messages to specific users or groups
4. Enjoy real-time communication!

## 🔒 Security Considerations

- Implement proper authentication
- Add input validation
- Use HTTPS
- Implement user presence tracking

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## 📝 License

This project is open-source and available under the MIT License.

## 🐛 Known Issues

- Limited error handling
- No persistent message storage
- Basic user management

## 📡 Future Roadmap

- [ ] User Authentication
- [ ] Message Persistence
- [ ] File Sharing
- [ ] Emoji Support
- [ ] Read Receipts

## 👨‍💻 Developers

- **Manthan Thakor** - _Initial work_

## 🙏 Acknowledgments

- Microsoft SignalR Team
- Tailwind CSS
- Font Awesome

---

**Happy Chatting!** 🎉
