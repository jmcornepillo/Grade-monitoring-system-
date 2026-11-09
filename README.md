# Grade-monitoring-system-

students = [

]

{"name": "ACUT JEZZLHER", "id": "BSIT001",

"section": "FB2-BSIT1-01"},

{"name": "ARDA RYAN CLINT", "id": "BSIT002",

"section": "FB2-BSIT1-01"},

{"name": "CORNIPILLO JM", "id": "BSIT003",

"section": "FB2-BSIT1-01"},

{"name": "PEREQUITE MICHAEL", "id": "BSIT004",

"section": "FB2-BSIT1-01"},

{"name": "TANAJURA LIM", "id": "BSIT005",

"section": "FB2-BSIT1-01"}

grades = []

subjects = [

"Mathematics",

"English",

"Science",

"Filipino"

]

SECTION = "FB2-BSIT1-01"

MAX STUDENTS = 30

# FEATURE 1: REGISTER STUDENT

def register_student():

if len(students) >= MAX STUDENTS:

print("\nStudent limit reached. Only 30 students are allowed.")

return

student_name = input("Enter Student Name: ").strip()

student_id = input("Enter Student ID: ").strip()

if not student name or not student id:
