# PoseFitAI

PoseFitAI is an innovative web-based fitness application that addresses common challenges in traditional exercise routines, such as lack of personalized guidance and real-time feedback. Utilizing advanced AI technologies like MediaPipe and React, PoseFitAI offers precise posture detection and analysis for exercises such as planks and squats. Users receive real-time feedback to improve exercise form, reduce injury risk, and enhance workout effectiveness. The platform offers a comprehensive and user-centric training experience, with guided sessions tailored to individual needs. PoseFitAI’s scalable design ensures ongoing innovation, making personalized coaching accessible and affordable to all users, regardless of location or experience.

## Features

- **User Authentication**
  - Login
  - Signup

- **Exercises**
  - **Plank**
    - Analyze exercise count
    - Provide feedback on correct and incorrect form
  - **Squat**
    - Analyze exercise count
    - Provide feedback on correct and incorrect form

- **Profile**
  - Track correct and incorrect counts
  - View feedback graphs

- **Session History**
  - Record previous sessions
  - Include session duration, correct/incorrect counts, start time, and end time

## Tools and Technologies

- **Frontend**
  - React
  - Tailwind CSS

- **Backend**
  - Flask
  - PostgreSQL ORM (ElephantSQL)

- **AI and Posture Detection**
  - MediaPipe Pose

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js
- Python
- PostgreSQL (for local development) or ElephantSQL (for cloud database)

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/SarmadNaroo/PoseFitAI-Personal-AI-fitness-trainer-with-Mediapipe-pose-analysis.git
    cd PoseFitAI
    ```

2. **Frontend setup**

    ```bash
    cd PoseFitAI-frontend-react
    npm install
    npm start
    ```

3. **Backend setup**

    ```bash
    cd PoseFitAI-backend-flask
    python -m venv poseenv
    source poseenv/bin/activate  # On Windows use `poseenv\Scripts\activate`
    pip install -r requirements.txt
    ```

4. **Configure ElephantSQL**

    - Create an ElephantSQL account and set up a PostgreSQL database.
    - Update your database configuration in the backend settings with the ElephantSQL connection string.

5. **Run the backend**

    ```bash
    python run.py
    ```

6. **Run the application**

    Make sure both the frontend and backend servers are running.

    ```bash
    # Frontend
    cd PoseFitAI-frontend-react
    npm start

    # Backend
    cd PoseFitAI-backend-flask
    source poseenv/bin/activate  # On Windows use `poseenv\Scripts\activate`
    python app.py
    ```

### Usage

1. **Sign up** for a new account.
2. **Log in** with your credentials.
3. Start a workout session by selecting an exercise (Plank or Squat).
4. Follow the on-screen instructions and receive real-time feedback on your form.
5. Check your profile to view your progress and feedback graphs.
6. Review your session history to see details of your previous workouts, including duration, correct/incorrect counts, start time, and end time.

## Screenshots

Here are some screenshots of the application:

![login](https://github.com/user-attachments/assets/5915224b-abdf-4ed6-9937-ecc66807e462)
*Login Screen*

![signup](https://github.com/user-attachments/assets/ee19b07d-8415-4f11-b17d-3fb897204901)
*Signup Screen*

![exercises](https://github.com/user-attachments/assets/43aef011-6920-4315-90ee-7f5789c39d63)
*Exercises Screen*

![squat](https://github.com/user-attachments/assets/0ad46c9b-b757-4e6e-ad6d-0d037f12eb96)
*Squar Exercises*

![profile](https://github.com/user-attachments/assets/2e8455c8-fd31-4dc7-9c25-c2933ade77e2)
*Profile Page*

![feedback graphs](https://github.com/user-attachments/assets/8067d6a6-1a4b-463f-a9e7-d103ef471334)
*Feedback graphs*

![session history](https://github.com/user-attachments/assets/fa3a7ebf-8685-453c-8af6-68d7d2bc13a1)
*Session history*

## Contributing

We welcome contributions to PoseFitAI! If you would like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Repository

[PoseFitAI GitHub Repository](https://github.com/SarmadNaroo/PoseFitAI-Personal-AI-fitness-trainer-with-Mediapipe-pose-analysis)
