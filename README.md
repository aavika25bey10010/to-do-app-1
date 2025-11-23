TO DO LIST APP
overview of the project:
This project is a lightweight task manager that runs entirely in the terminal.
Tasks are saved locally in a tasks.json file so your data stays even after closing the program.
It includes some fun productivity messages, innovative features (focus mode, automatic deadline warnings), and a clean task-tracking workflow.
Features:
1.Add tasks with optional deadlines
2.Mark tasks as completed
3.Automatic daily completion streak messages
4.Deadline alerts (overdue / due soon)
5.Focus Mode → shows pending tasks one by one
6.Tasks saved in JSON
7.Clean terminal interface
8.No external frameworks required
Technologies / Tools Used:
Python 3
Built-in modules:
json
datetime
os
Installation & Running the Project:
1. Clone or download the project
git clone <your-repo-link>
cd to-do-list
or simply save the main.py and tasks.json (empty) in a folder.
2. Make sure Python 3 is installed
Check:
python --version
3. Run the program
python main.py
Your menu will appear:
1. add task
2. view task
3. mark task done
4. focus mode
5. exit

How to Test the App:
Test: Adding a task
1. Run the program
2. Press 1
3. Enter a task name
4. (Optional) Enter deadline
Expected → Task saved in tasks.json

Test: Viewing tasks:
1. Press 2
Expected → Task list printed with statuses and deadlines.

Test: Completing a task:
1. Add 2–3 tasks
2. Press 3
3. Enter task number
Expected →
Task marked as done
Completion date saved
Motivational message shown
Test: Deadline warnings

Add tasks with deadlines:
Today
1 day ahead
Past date
Expected →
“overdue”
“deadline coming (X days left)”
Test: Focus Mode
1. Press 4
Expected →
Shows pending tasks one by one until done.














