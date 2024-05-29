student_grades = {}
def add_update_grade(student_name, grade):
    student_grades[student_name] = grade
    print(f"grade for {student_name} has been added/updated to:{grade}")
def delete_grade(student_name):
    if student_name in student_grades:
        del student_grades[student_name]
        print(f"Grade for {student_name} has been deleted")
    else:
        print(f"No record found for {student_name}.")
def display_all_grades():
    for student_name, grade in student_grades.items():
        print(f"{student_name}:{grade}")

add_update_grade("John Doe", 88)
add_update_grade("Jane Smith", 93)
display_all_grades()
delete_grade("John Doe")
display_all_grades()

add_update_grade("John Doe", 88)
add_update_grade("Jane Smith", 93)
display_all_grades()
delete_grade("John Doe")
display_all_grades()

add_update_grade("John Doe", 88)
add_update_grade("Jane Smith", 93)
display_all_grades()
delete_grade("John Doe")
display_all_grades()


