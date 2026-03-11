# MATE Notes Storage

> **PDF CDN storage repository for the [MATE Notes](https://mate-notes.vercel.app) website — built for GTU (Gujarat Technological University) students.**

This repository acts as a free CDN backend using [jsDelivr](https://www.jsdelivr.com/). All note PDFs uploaded here are served directly to the MATE Notes web app via jsDelivr's global CDN network.

---

## 🌐 Website

**[https://mate-notes.vercel.app](https://mate-notes.vercel.app)**

---

## 📂 Folder Structure

```
MATE-Notes-Storage/
├── sem1/          # Semester 1
├── sem2/          # Semester 2
├── sem3/          # Semester 3
├── sem4/          # Semester 4
├── sem5/          # Semester 5
├── sem6/          # Semester 6
├── sem7/          # Semester 7
└── sem8/          # Semester 8
```

### Semester → GTU Branch Mapping

| Folder | Semester | Applicable Branches                     |
|--------|----------|-----------------------------------------|
| sem1   | Sem 1    | All BE branches (CE, IT, EC, EE, ME, Civil) |
| sem2   | Sem 2    | All BE branches (CE, IT, EC, EE, ME, Civil) |
| sem3   | Sem 3    | CE, IT, EC, EE, ME, Civil               |
| sem4   | Sem 4    | CE, IT, EC, EE, ME, Civil               |
| sem5   | Sem 5    | CE, IT, EC, EE, ME, Civil               |
| sem6   | Sem 6    | CE, IT, EC, EE, ME, Civil               |
| sem7   | Sem 7    | CE, IT, EC, EE, ME, Civil               |
| sem8   | Sem 8    | CE, IT, EC, EE, ME, Civil               |

> **Supported Branches:** Computer Engineering (CE), Information Technology (IT), Electronics & Communication (EC), Electrical Engineering (EE), Mechanical Engineering (ME), Civil Engineering (Civil)

---

## 🚀 jsDelivr CDN URL Format

Once a PDF is pushed to this repository, it can be accessed instantly via jsDelivr using the following URL pattern:

```
https://cdn.jsdelivr.net/gh/YOUR_USERNAME/MATE-Notes-Storage@main/{folder}/{filename}.pdf
```

### Examples

```
# Semester 1 Physics notes
https://cdn.jsdelivr.net/gh/YOUR_USERNAME/MATE-Notes-Storage@main/sem1/physics-unit1.pdf

# Semester 3 Data Structures (CE/IT)
https://cdn.jsdelivr.net/gh/YOUR_USERNAME/MATE-Notes-Storage@main/sem3/data-structures-unit2.pdf

# Semester 5 Computer Networks (CE)
https://cdn.jsdelivr.net/gh/YOUR_USERNAME/MATE-Notes-Storage@main/sem5/computer-networks-unit3.pdf
```

> Replace `YOUR_USERNAME` with the actual GitHub username of this repository's owner.

---

## 📋 File Naming Convention

Use lowercase, hyphen-separated names for consistency:

```
{subject-name}-unit{unit-number}.pdf
```

**Examples:**
- `physics-unit1.pdf`
- `data-structures-unit3.pdf`
- `digital-electronics-unit2.pdf`
- `engineering-maths-unit4.pdf`

---

## 🤝 Contributing

We welcome contributions from GTU students! Follow these steps to add new notes:

### Steps to Add a PDF

1. **Fork** this repository by clicking the "Fork" button at the top right.

2. **Clone** your forked repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/MATE-Notes-Storage.git
   cd MATE-Notes-Storage
   ```

3. **Add your PDF** to the correct semester folder:
   ```bash
   # Example: adding a sem3 subject PDF
   cp /path/to/your/notes.pdf sem3/subject-name-unit1.pdf
   ```

4. **Commit and push** your changes:
   ```bash
   git add .
   git commit -m "Add [Subject Name] Unit [X] notes for Sem [X]"
   git push origin main
   ```

5. **Open a Pull Request** on GitHub with:
   - Subject name and semester
   - GTU subject code (if available)
   - Branch it applies to

### Guidelines

- ✅ Only upload **GTU syllabus** study materials
- ✅ Use the naming convention: `subject-name-unit{n}.pdf`
- ✅ Place files in the **correct semester folder**
- ✅ Ensure PDFs are **readable and not corrupt**
- ❌ Do not upload copyrighted textbook scans
- ❌ Do not upload files unrelated to GTU academics

---

## 📄 License

This repository is maintained for educational purposes. All notes are contributed by GTU students for GTU students.

---

*Maintained by the MATE Notes team — [https://mate-notes.vercel.app](https://mate-notes.vercel.app)*
