# 101393080LabTest2Comp3133

This is my submission for COMP 3133 – Lab Test 2. The application is built using Angular and fetches data from the SpaceX API. It includes mission listings, filters, and detailed views of each mission. Styling is enhanced using Angular Material.

---

## 🔧 Features Implemented

- ✅ Display list of SpaceX missions
- ✅ Filter missions by **Launch Year**, **Launch Status**, and **Landing Status**
- ✅ Display mission patch image, mission name, year, and details
- ✅ View mission details using filtered criteria
- ✅ Angular Material UI components for styling
- ✅ Responsive and clean layout

---

## 🧲 How to Run the App Locally

### Development Server
```bash
ng serve
```
Navigate to `http://localhost:4200/`. The app will reload if you change any source files.

---

## 📂 Folder Structure
```
src/
├── app/
│   ├── missionlist/       # Mission list and filter components
│   ├── models/            # Interface for SpaceX mission data
│   ├── services/          # API service to fetch SpaceX data
├── assets/screenshots/   # Screenshots for D2L submission
```

---

## 📸 Screenshots

### 🔹 Main Mission List Page
![Mission List](src/assets/screenshots/missionlist.png)

### 🔹 Filters Applied (Successful Launch + Landing)
![Filter Success](src/assets/screenshots/filter-success-success.png)

### 🔹 Filters Applied (Failed Launch + Successful Landing)
![Filter Launch Fail](src/assets/screenshots/filter-fail-success.png)

### 🔹 Filters Applied (Successful Launch + Failed Landing)
![Filter Landing Fail](src/assets/screenshots/filter-success-fail.png)

### 🔹 Filters Applied (Failed Launch + Failed Landing)
![Filter All Fail](src/assets/screenshots/filter-fail-fail.png)

---

## 📁 Deployment (Optional)
If hosting on platforms like Vercel, Render, or Netlify:

```bash
ng build --configuration=production
```
Upload the `dist/` folder to your preferred static host.

---

## 📬 Submission Requirements
- [x] GitHub repository: ✅ [Link to this repo](https://github.com/DongryeolPark/DongryeolPark-101393080-lab-test2-comp3133)
- [x] Screenshots uploaded separately to D2L ✅
- [x] Optionally include a video walkthrough (if required)

---

## 📚 Additional Resources

For more info on Angular CLI:
[Angular CLI Documentation](https://angular.dev/tools/cli)

---

> Student ID: **101393080**  
> Name: **Dongryeol Park**  
> Course: **COMP 3133 - Full Stack Development**

