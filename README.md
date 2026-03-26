# pado-aur-seekho
"Pado Aur Seekho" is a simple library management system for students and librarians. Students can use this for issuing books in advance and librarian can use this to approve/decline the requests sent by the students and some more similar functions are available for librarian. 
## 🔗 Live Demo
👉 https://pado-aur-seekho.netlify.app/

---

## 🚀 Features

### 👨‍🎓 Student Features
- Login using Student ID
- Browse available books
- Request multiple books (up to 3)
- View request status (Pending / Approved / Rejected)
- Track return deadlines
- View overdue fines
- Check complete request history

### 👨‍💼 Librarian Features
- Login as Librarian
- View all student requests
- Approve or reject requests
- Automatic book availability update
- Manage book returns
- Update returned books
- Track all issued books

---

## 🛠️ Technologies Used

- **HTML** – Structure of web pages  
- **CSS** – Styling and layout  
- **JavaScript** – Application logic and interactivity  
- **LocalStorage** – Client-side data storage  
- **Netlify** – Deployment and hosting  

---

## ⚙️ How It Works

1. Students log in and request books.
2. Requests are stored in LocalStorage.
3. Librarian reviews requests:
   - Approves → book count decreases
   - Rejects → no change
4. Student can track request status.
5. When books are returned:
   - Librarian marks as returned
   - Book count increases
6. System calculates overdue fines automatically.

---


## 📌 Key Concepts Implemented

- Role-based access (Student / Librarian)
- Dynamic UI updates using JavaScript
- Data persistence using LocalStorage
- Form validation and user input handling
- Book inventory management system
- Status tracking and fine calculation

---

## 🔮 Future Improvements

- Add backend (Firebase / Node.js)
- Real authentication system
- Database integration
- Multi-user support
- Email notifications
- Admin dashboard

---

## 👨‍💻 Author

**Mandava Pardha Saradhi**  
Roll No: Y23CD114  
CSE (Data Science)  
R.V.R. & J.C. College of Engineering  

---

## 📄 License

This project is developed for educational purposes.
