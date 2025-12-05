📌 Overview

This project demonstrates a concurrent Client–Server architecture implemented in Go (Golang). It showcases how goroutines, channels, and the Go net package can be used to build efficient concurrent network systems.

🎥 Video Explanation


Uploading VID_20251205_224058.mp4…


Click below to watch the full explanation video:

Replace VIDEO_ID with the actual YouTube video ID.

🚀 Features

Concurrent server handling multiple clients

Goroutine-based connection processing

Channel-based message synchronization

Graceful shutdown

Simple, clean Go modules structure

📂 Project Structure
/client
    client.go
/server
    server.go
README.md
go.mod

🛠️ How to Run
1. Clone the repository
git clone https://github.com/yourusername/yourproject.git
cd yourproject

2. Start the server
go run server/server.go

3. Run the client
go run client/client.go


Multiple clients can be started at the same time.

🧠 How It Works (Concurrency Summary)

The server listens for TCP connections using net.Listen.

Each client connection is managed in a goroutine, allowing concurrency.

Channels synchronize communication or logging.

The client connects to the server and sends/receives messages concurrently using goroutines.

👤 Author

Ibrahim Hisham Alkhouly
