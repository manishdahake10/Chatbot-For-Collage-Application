# Chatbot for College Application (Shiksha Sharthi)

## Overview
This is a Chatbot for a College Application system built using PHP, JSON, HTML, CSS, JavaScript, Bootstrap, and SQL. The system enables users (students or prospective students) to interact with a chatbot for inquiries related to the college, such as course details, admission process, exam schedules, etc. It provides an interactive and engaging way for users to get answers to frequently asked questions and perform simple tasks.

## Features
- Chat with the bot for general college-related queries.
- Ask about available courses, admission procedures, fees, and deadlines.
- Receive dynamic responses based on user input.
- Simple, user-friendly interface with an integrated chatbot.
- Responsive design using Bootstrap for mobile and desktop compatibility.
- Store user conversations and queries in a database for future analysis or improvement.

## Technologies Used
- **PHP**: Server-side scripting language used to process user inputs and generate responses.
- **HTML/CSS**: For structuring and styling the chatbot interface.
- **JavaScript**: For dynamic interaction with the chatbot and real-time communication with the server.
- **Bootstrap**: Used to create a responsive and modern user interface.
- **SQL**: For managing user queries and chatbot responses in the database.
- **JSON**: Used for data interchange between client and server.

## Requirements
- A server with PHP support (e.g., Apache or Nginx).
- MySQL or MariaDB for database management.
- A modern web browser (e.g., Chrome, Firefox).
  
## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/manishdahake10/ChatbotForCollegeApplication.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ChatbotForCollegeApplication
    ```

3. Set up the database:
    - Create a new MySQL database (e.g., `college_chatbot_db`).
    - Import the database schema from `database.sql` into the newly created database.

4. Configure the database connection:
    - Edit the `config.php` file to set your database connection details (host, username, password, database name).

5. Start the server (if using Apache or Nginx):
    - Place the project files in the server's root directory (e.g., `/var/www/html` for Apache on Linux).
    - Access the system through `http://localhost` or your server's address.

6. The chatbot application should now be ready to use.

## Usage
Once the system is running, you can access the chatbot interface through your browser. Here's how to use it:

- **Start a conversation**: Type your query (e.g., "What are the available courses?" or "How can I apply for admission?") in the chat window and hit "Send."
- **Receive responses**: The chatbot will respond to your query with predefined answers or guide you to the relevant sections of the college's website or information.
- **View Chat History**: You can review past conversations that have been stored in the database.
- **Exit the chatbot**: Close the chatbot window or refresh the page to end the interaction.

### Output Screenshots

**Chatbot Interface**:<br>
![Chatbot Interface](https://github.com/manishdahake10/ChatbotForCollegeApplication/assets/chatbot_interface.png)<br><br>

**Example Query Interaction**:<br>
![Chatbot Query](https://github.com/manishdahake10/ChatbotForCollegeApplication/assets/query_example.png)<br><br>

## Code Structure
The project consists of the following structure:

- `index.php`: The main file that handles user input and displays the chatbot interface.
- `chatbot.php`: Handles the chatbot's responses based on user input.
- `config.php`: Contains the database connection configuration.
- `database.sql`: SQL file containing the schema for storing user queries and chatbot responses.
- `style.css`: Custom CSS file for styling the chatbot and the web page.
- `chatbot.js`: JavaScript file for managing dynamic interaction and communication between the user and the server.

## Contribution
Feel free to fork this repository and contribute by opening issues or pull requests. Suggestions for additional features, improvements, or bug fixes are always welcome!

## Author
**Your Name**  
GitHub: [manishdahake10](https://github.com/manishdahake10)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
