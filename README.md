**Quadratic Equation Solver 🧮**
         
          A simple web application to solve quadratic equations (ax² + bx + c = 0) using Flask and Docker. Users can enter values for a, b, and c, and the app calculates the roots of the equation.

**Table of Contents**
   1. Features
   2. Technologies Used
   3. Installation
   4. Usage
   5. Docker Support
   6. Project Structure
      
**Features ✨**

  ✔️ Solve quadratic equations using factoring and quadratic formula
  ✔️ Handles real and complex roots
  ✔️ User-friendly HTML interface
  ✔️ Error handling for invalid inputs
  ✔️ Dockerized for easy deployment
  
**Technologies Used 🛠️**
    Python 3.9
    Flask (Backend framework)
    HTML + Jinja2 (Frontend)
    Docker (Containerization)
    Gunicorn (WSGI Server)
    
**Installation 🛠️**

**Ensure you have the following installed:**

  ✅ Python 3.9+
  ✅ pip (Python Package Manager)
  ✅ Git
  ✅ Docker (Optional, for containerized deployment)

1️⃣ **Clone the repository**

            git clone https://github.com/yourusername/Quadratic_Equation_Solver.git
            cd Quadratic_Equation_Solver
            
**2️⃣ Set up a virtual environment (Optional but recommended)**
           
            python -m venv venv
            source venv/bin/activate   # On Mac/Linux
            venv\Scripts\activate      # On Windows
            
3️⃣ **Install dependencies**

            pip install -r requirements.txt
4️⃣ **Run the Flask app**

            python app.py
            
**The app will run at: http://127.0.0.1:5000/ 🎉**

**Usage 🚀**

      1️⃣ Open a web browser and go to: http://127.0.0.1:5000/
      2️⃣ Enter values for a, b, c in the input fields.
      3️⃣ Click Solve to get the roots of the equation.
      4️⃣ The result will be displayed below the form.
      
**Docker Support 🐳**

**Run the app inside a Docker container:**

**1️⃣ Build the Docker image**

      docker build -t quadratic_solver .
      
** 2️⃣ Run the container**

      docker run -p 5000:5000 quadratic_solver
      
Now, visit http://localhost:5000/ in your browser.

**Project Structure 📂**


        Quadratic_Equation_Solver/    # Root project folder
        │── app.py                    # Main Flask application file
        │── Dockerfile                 # Docker configuration
        │── requirements.txt           # List of dependencies
        │── README.md                  # Project documentation
        │
        ├── templates/                 # HTML templates (Frontend UI)
        │   ├── index.html             # Main user interface for input and output
        │
        ├── static/                    # Static files (CSS, JS, Images)
        │
        │   ├── images/                # Folder for storing images
        │   │   ├── output1.png        # Example output image 1
        │   │   ├── output2.png        # Example output image 2
        │   │   ├── output3.png        # Example output image 3
        



