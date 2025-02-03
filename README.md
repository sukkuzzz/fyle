
Live Link -> [https://fyle-puce.vercel.app/]
Email -> sukriti.001sharma@gmail.com
site -> sukritisharma.site

<img width="1440" alt="Screenshot 2025-02-03 at 7 57 49 PM" src="https://github.com/user-attachments/assets/8d246de8-cb24-458e-aaac-75f0ad053626" />
<img width="1440" alt="Screenshot 2025-02-03 at 7 57 23 PM" src="https://github.com/user-attachments/assets/88e24afb-46b0-4323-b130-ede857470ba5" />
<img width="1440" alt="Screenshot 2025-02-03 at 7 57 55 PM" src="https://github.com/user-attachments/assets/092b99bd-00c5-4579-9a5f-c64449a7ad0c" />


# Health Challenge Tracker 

A simple Angular-based workout tracking application that allows users to add and view their workouts in a tabular format.

## 🚀 Features
- Add new workouts using a text input field.
- Display the list of added workouts in a dynamic table.
- Uses Angular standalone components for modular design.
- Implements two-way data binding using `ngModel`.

## 🛠 Technologies Used
- **Angular** (Standalone Components)
- **TypeScript**
- **HTML & CSS**
- **TailwindCSS**

## 📦 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/sukkuzzz/fyle.git
   cd fyle
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Run the application:
   ```sh
   ng serve
   ```
4. Open your browser and go to:
   ```sh
   http://localhost:4200
   ```

## 📂 Project Structure
```
📦 workout-tracker
├── 📁 src
│   ├── 📁 app
│   │   ├── 📁 components
│   │   │   ├── 📁 add-user
│   │   │   │   ├── add-user.component.ts
│   │   │   │   ├── add-user.component.html
│   │   │   │   ├── add-user.component.css
│   │   │   │   ├── add-user.component.spec.ts
│   │   │   │   ├── add-user.model.ts
│   │   │   ├── 📁 progress-chart
│   │   │   │   ├── progress-chart.component.ts
│   │   │   │   ├── progress-chart.component.html
│   │   │   │   ├── progress-chart.component.css
│   │   │   │   ├── progress-chart.component.spec.ts
│   │   │   │   ├── progress-chart.model.ts
│   │   │   ├── 📁 users
│   │   │   │   ├── users.component.ts
│   │   │   │   ├── users.component.html
│   │   │   │   ├── users.component.css
│   │   │   │   ├── users.component.spec.ts
│   │   │   │   ├── users.model.ts
│   │   ├──📁 services
│   │   │   ├── 📁 add-user
│   │   │   │   ├── add-user.service.spec.ts
│   │   │   │   ├── add-user.service.ts
│   │   │   ├── 📁 chart
│   │   │   │   ├── chart.service.ts
│   │   │   │   ├── chart.service.spec.ts
│   │   │   ├── 📁 dialog
│   │   │   │   ├── dialog.service.ts
│   │   │   │   ├── dialog.service.spec.ts
│   |   ├── app.component.ts
│   |   ├── app.component.spec.ts
│   |   ├── app.component.html
│   |   ├── app.config.ts
│   |   ├── app.model.ts
│   |   ├── app.routes.ts
|   ├── index.html
|   ├── main.ts
|   ├── style.css
├── angular.json
├── package.json
└── README.md
```

## 📝 Usage
1. Enter a workout name in the input field.
2. Click **Add Workout**.
3. The workout will be displayed in the table below.

## 🛠 Troubleshooting
If the table does not update after adding a workout:
- Ensure `[(ngModel)]` is correctly bound in `add-user.component.html`.
- Check if `@Output()` in `add-user.component.ts` emits data properly.
- Verify that `@Input()` is used in `users.component.ts`.

## 💡 Future Enhancements
- Add workout categories (e.g., Running, Weightlifting, Swimming).
- Implement local storage to save workouts.
- Include a delete/edit feature.

## 🤝 Contributing
1. Fork the repository.
2. Create a new feature branch:
   ```sh
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```sh
   git commit -m "Added new feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature-name
   ```
5. Open a pull request.

For any issues or suggestions, feel free to reach out!



