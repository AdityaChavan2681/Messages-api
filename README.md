🧠 Messages API — Rails-Based API Practice Project

📌 Overview
This repo was built to explore API-driven development using Ruby on Rails. It’s designed as a backend-only service for testing endpoints via Postman, focusing on clean routing, controller logic, and JSON responses.

🛠️ Tech Stack
Framework: Ruby on Rails (API mode)

Database: SQLite / PostgreSQL

Tools: Postman, Rails CLI, ActiveRecord

🚀 Features
RESTful endpoints for message creation and retrieval

JSON-based responses for easy API consumption

No frontend views—pure backend logic

Ideal for Postman testing and API experimentation

📁 Structure Highlights
app/controllers/messages_controller.rb: Handles API requests

app/models/message.rb: Defines message schema

config/routes.rb: Sets up RESTful routes

db/schema.rb: Reflects current database structure

🧪 How to Run Locally
bash
git clone https://github.com/AdityaChavan2681/Messages-api.git
cd Messages-api
bundle install
rails db:create db:migrate
rails server
Use Postman to send requests to http://localhost:3000/messages.

🧠 Reflection
This project helped me understand Rails as an API engine, focusing on clean controller logic and endpoint behavior. It’s a lean build that sharpened my skills in backend testing and request handling.
