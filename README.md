# todo-sync-app

# To-Do Sync App

A cross-platform To-Do application with a Python FastAPI backend and a planned iOS/Android frontend. This project allows users to create, update, delete, and sync tasks across devices.

---

## Features
- Add, edit, delete, and mark tasks as complete.
- Sync tasks with a FastAPI backend.
- Planned mobile front-end using cross-platform frameworks.

---

## Tech Stack
### Backend
- **FastAPI**: Python-based web framework for REST API development.
- **SQLite**: Lightweight database for task storage.

### Frontend (Planned)
- **Flutter**: For cross-platform development (iOS and Android).

---

## Getting Started

### Prerequisites
1. Install Python (version 3.7 or higher).
2. Install Flutter (for planned mobile development).

---

### Setting Up the Backend
1. Clone the repository:
    ```bash
    git clone https://github.com/yesh/todo-sync-app.git
    cd todo-sync-app
    ```
2. Install dependencies:
    ```bash
    pip install fastapi uvicorn
    ```
3. Run the server:
    ```bash
    uvicorn main:app --reload
    ```
4. Access the API documentation:
    - Open your browser and navigate to `http://127.0.0.1:8000/docs`.

---

### Planned Features for Mobile App
- Display tasks fetched from the backend.
- Add new tasks with a simple form.
- Mark tasks as completed.
- Update and delete tasks.
  
---

## Project Structure
todo-sync-app/ │ ├── backend/ │ ├── main.py # FastAPI server │ └── models.py # Task model │ └── frontend/ ├── flutter/ # Planned Flutter app └── react-native/ # Optional React Native implementation


---

## Contributing
We welcome contributions! Here's how you can get involved:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
If you have any questions or suggestions, feel free to reach out:
- **Email**: yeswanthsoma83@example.com
- **GitHub**: [yesh2344](https://github.com/yesh2344)

## Copyrights

@Yeswanth Soma All Copyrights Reserved
