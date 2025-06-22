📘 Student Report Card DApp

A decentralized web application (DApp) built using the Internet Computer Protocol (ICP), designed to manage student performance records. Users can add, update, and delete student information, calculate average scores and grades, and generate clean, downloadable PDF report cards.

🔐 Powered by Internet Computer (DFINITY), secured and hosted on the blockchain.
🧠 About the Project

This project aims to provide a simple yet powerful decentralized system to track student academic performance in real-time. By leveraging Rust and React, the app integrates a robust backend with an interactive frontend. The PDF generation allows for offline portability and professional documentation of performance.


📦 Prerequisites

Make sure you have the following installed:

Node.js & npm

DFX SDK

Rust & Cargo

# Install WebAssembly target

rustup target add wasm32-unknown-unknown

# Optionally install cargo-audit (for security auditing)

cargo install cargo-audit

🚀 Setup & Run

# Clone the repo

git clone https://github.com/your-username/student-report-card-dapp.git

cd student-report-card-dapp

# Install frontend dependencies

npm install

# Start local replica

dfx start --background

# Deploy canisters

dfx deploy

Open the app at: http://localhost:4943

🖨 PDF Report Generation

Each student gets a clean, styled PDF report card including:

📌 Name

✍️ Total Marks

📚 Subjects

📈 Average Marks

🏅 Grade (A–D based on performance)

Use the Download PDF Report Cards button to export all student reports.

🗃 Backend Logic

The backend is implemented in Rust and handles:

add_student: Insert/update student entry
dback are welcome!

📜 License

This project is open-source and available under the MIT License.
