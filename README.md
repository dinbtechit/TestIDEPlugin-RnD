# An IDE for Testing

!!! info
    Inspired by Open Test Framework

## 🎯 Goals
- Build an intellij Plugin to Record/Play/Manage test cases for testing websites

# ⚗🧪 R&D 
1. Understand Intellij JetBrain Plugin Development: 
    - Build a hello world plugin in Intellij
    - understand how to create/modify UI in Intellij
    - Code generation in Intellij
    - Learn about Intellij's pico container
2.  What is the best framework? selenium, puppeteer (kolin or Nodejs) or playwright (Java).
    > It has to be Java or Kolin related. Inorder to integrate with Intellij. Too bad should we chosen a VScode extention instead?
3.  Understand how Jasmine and selenium works:
    - Read about Jasmine and Selenium.
    - Alternately we can use Open Test. But its yml based. So debugging options are virtually impossible.
4. Build E2E architecture for Test IDE.  
    - Client (Browser) ➡ Server (Intellij -> Lightweight HTTP server)
    - https://localhost:90909090909/api/events/{{click}}
    - https://localhost:90909090909/api/events/{{keystrokes}}
    - https://localhost:90909090909/api/events/{{command}}
    
----

# 👩‍💻 Development

coming soon...

