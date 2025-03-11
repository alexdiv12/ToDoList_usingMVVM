# ToDoList_usingMVVM

This is a simple To-Do List application built using SwiftUI and the Model-View-ViewModel (MVVM) architecture.

## Features

* Add new tasks to the list.
* Mark tasks as completed.
* Persistent data storage.

## Architecture

This project follows the MVVM architecture to separate concerns and improve testability:

* **Model:** Defines the data structure for a task (e.g., `Task` struct).
* **View:** The SwiftUI views responsible for displaying the UI and handling user interactions (e.g., `ListView`, `AddItemView`).
* **ViewModel:** The `ListViewModel` class acts as an intermediary between the Model and View, managing the application's state and logic.

## Technologies Used

* SwiftUI
* MVVM architecture
* Git for version control

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/alexdiv12/ToDoList_usingMVVM.git](https://github.com/alexdiv12/ToDoList_usingMVVM.git)
    ```

2.  **Open the project in Xcode:**

    * Navigate to the cloned directory.
    * Open the `ToDoList_usingMVVM.xcodeproj` file.

3.  **Run the app:**

    * Select a simulator or connect your iOS device.
    * Click the "Run" button in Xcode.

## Future Enhancements

* Implement data persistence (e.g., using Core Data or UserDefaults).
* Add task editing and deletion functionality.
* Improve UI and user experience.
* Add categories or tags for tasks.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## Author

* Divyanshu Rai
