# 📋Task Beat

Task Beat is a simple and clean Android app for managing tasks using custom categories.
Users can create categories, add tasks, filter by category, update tasks, and delete categories or tasks through modern bottom sheets.

⸻

## ✨ Features
	•	Empty state screen when no categories exist
	•	Create custom categories (e.g., gym, work, study)
	•	Create tasks inside each category
	•	Filter tasks by category or show ALL
	•	Update tasks through a bottom sheet
	•	Delete categories (with warning)
	•	Delete individual tasks
	•	Smooth UI transitions and modern design

⸻

## 🧠 How It Works
	•	Each category has its own list of tasks
	•	Room Database stores:
	•	CategoryEntity
	•	TaskEntity
	•	Bottom Sheets are used for:
	•	Creating a category
	•	Creating or updating tasks
	•	Showing warnings/info
	•	RecyclerViews display categories (chips) and tasks   

  ## 📸 ScreenShots   
  <img width="200" src="https://github.com/user-attachments/assets/c3153d46-d391-49ba-ba1b-01c421860684" />
<img width="200" src="https://github.com/user-attachments/assets/c92501f1-0d44-4ff5-a2ce-44515531c70f" />
<img width="200" src="https://github.com/user-attachments/assets/71928269-98cb-4661-99f2-b91ffa1b1436" />
<img width="200" src="https://github.com/user-attachments/assets/eaa31367-4be2-4ae9-afa7-f41930f2ba59" />
<img width="200" src="https://github.com/user-attachments/assets/4582e651-6e42-44a7-bb67-30693369414b" />
<img width="200" src="https://github.com/user-attachments/assets/79af3f1a-ccad-4bb0-ac6f-4d8d8418426f" />


⸻

## 🛠 Technologies Used
	•	Kotlin
	•	Android Studio
	•	Room Database
	•	RecyclerView + Adapters
	•	BottomSheetDialogFragment
	•	Material Design Components
	•	XML Layouts
	•	MVVM-like structure (UI Data classes)

## 📂 Project Structure
com.devspace.taskbeats   
 ├── CategoryDao   
 ├── CategoryEntity   
 ├── CategoryListAdapter   
 ├── CategoryUiData   
 ├── CreateCategoryBottomSheet    
 ├── CreateOrUpdateTaskBottomSheet   
 ├── InfoBottomSheet   
 ├── MainActivity   
 ├── TaskBeatDataBase   
 ├── TaskDao   
 ├── TaskEntity   
 ├── TaskListAdapter   
 └── TaskUiData   

## 🚀 How to Run
	1.	Clone the repository
	2.	Open it in Android Studio
	3.	Run the project on an emulator or real device

⸻

## Author (under the guidance of Roque buarque)   
Francisco Cleonis Costa de Souza   
Android Developer (Junior)   
📍 Bristol, UK  
🔗 GitHub: https://github.com/cleonissouza   
🔗 LinkedIn: https://www.linkedin.com/in/cleonis-souza/  
