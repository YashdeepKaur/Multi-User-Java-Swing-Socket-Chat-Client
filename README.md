# Multi-User-Java-Swing-Socket-Chat-Client

A graphical desktop chat client built using Java Swing, AWT, and standard Networking (`java.net`) libraries. It interfaces with an external chat server to facilitate real-time message broadcasting across connected instances.

## Features
- **Two-Stage Window Lifecycle:** Displays a login form to gather identity before unveiling the main chat workspace.
- **Background Stream Listener:** Utilizes a dedicated background execution thread (`Runnable`) to listen for incoming messages without blocking UI interaction.
- **Explicit Protocol Parsing:** Separates message payload routing from status notifications based on indicator prefixes.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c246b487-e11b-431d-a129-e2ef5c349edd" />
