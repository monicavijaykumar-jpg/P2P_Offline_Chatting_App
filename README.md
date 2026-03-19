Offline Chatting App (P2P) 📱💬

A decentralized Android messaging application that allows users to chat in real-time without an internet connection, cellular data, or a Wi-Fi router. This project is built using Kotlin and Jetpack Compose, leveraging Wi-Fi Direct (P2P) technology for seamless communication.


🚀 Key Features :

Zero Infrastructure: No internet, 4G/5G, or external servers required. Ideal for off-grid messaging.

Peer Discovery: Automatically scans and lists nearby active users using the Wi-Fi P2P API.

Direct Messaging: Establishes a secure, high-speed socket connection between two devices for instant chat.

Modern UI/UX: A clean and responsive interface designed with Jetpack Compose and Material 3 principles.

Uses: tecting in Remote areas within the distance of 50 mmeters.


🛠️ Tech Stack :

Language: Kotlin

UI Framework: Jetpack Compose

Networking: Wi-Fi Direct (P2P) API, Java Sockets

Architecture: MVVM (Model-View-ViewModel) for efficient state management.

Permissions: Seamless runtime handling for Nearby Devices and Location access.


⚙️ How It Works :

Permissions: The app requests necessary networking permissions upon launch.

Discovery: Click "Search Nearby Phones" to find other users nearby.

Connection: Select a peer from the list to initiate a connection handshake.

Chatting: Once the direct link is established, users can send and receive text messages instantly via local sockets.


💡 Why I built this? (The Inspiration) :

The idea for this project was born during a flood emergency when my friends and I were unable to communicate due to a complete mobile network and tower failure. I realized how critical it is to have a communication tool that doesn't depend on external infrastructure. This inspired me to develop a decentralized solution—an Offline Chatting App—that uses direct device-to-device signals to keep people connected when traditional networks fail.


👨‍💻 Developed By

Monica Computer Science Undergraduate | Aspiring App Developer and Designer

  
