# Reminder App

A feature-rich reminder application to help users manage tasks efficiently with a seamless experience.

![Onboarding Screen 1](assets/Onboarding-1.png)
![Onboarding Screen 2](assets/Onboarding-2.png)
![Onboarding Screen 3](assets/Onboarding-3.png)
![Home Screen](assets/Home.png)

## Features

### 1. **User Onboarding**
   - Interactive walkthrough introducing the app's core features.
   - Option to skip or revisit onboarding.

### 2. **Login and Signup**
   - Secure user authentication with email/social logins.
   - Password validation and easy password reset.

### 3. **Task Management**
   - Add, edit, and categorize tasks with deadlines.
   - Set recurring tasks, due dates, and reminders.
   - Sort and filter tasks by status and priority.

### 4. **Completed Tasks**
   - Track completed tasks and view history.
   - Archive or delete tasks for a clutter-free experience.
   - Celebration animations on task completion.

### 5. **Push Notifications**
   - Set custom push notifications and email reminders.
   - Snooze functionality for task reminders.
   - 
### 6. **Insights & Reports**
   - Track productivity with stats and progress reports.
   - View daily/weekly task summaries.

---

## Tech Stack

### Frontend
- **React Native**: Cross-platform mobile app development.
- **Expo**: Streamlined development and testing.
- **TypeScript**: Ensures type-safe, reliable code.

### Backend
- **Node.js**: Server-side logic.
- **Express.js**: Robust API framework.
- **MongoDB**: Efficient, secure data storage.

### Additional Tools
- **Git**: Version control for collaborative work.
- **Babel**: JavaScript transpilation.
- **Yarn/NPM**: Dependency management.

---

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vipul-Mhatre/Reminder-App.git
   cd reminder-app
   ```

2. **Install dependencies**:
   ```bash
   yarn install
   # or
   npm install
   ```

3. **Start the Expo development server**:
   ```bash
   expo start
   ```

4. **Backend setup**:
   - Navigate to the `api` directory and set up the backend:
     ```bash
     cd api
     npm install
     npm start
     ```
   - Ensure MongoDB is running locally or use a cloud-hosted MongoDB instance.

5. **Run on a device**:
   - Use the Expo Go app (iOS/Android) or an emulator to test the app.

---

## Directory Structure

```
reminder/
├── api/               # Backend code
├── app/               # Application configurations
├── assets/            # Static files (images, fonts)
├── components/        # Reusable UI components
├── scripts/           # Custom scripts
├── App.js             # Main app entry point
├── package.json       # Dependencies and scripts
├── tsconfig.json      # TypeScript configuration
```

---

## Contribution Guidelines

We welcome contributions! Please follow the steps below:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Description of changes"`.
4. Push the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).
