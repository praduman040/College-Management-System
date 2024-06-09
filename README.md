# College-Management-System
import java.util.ArrayList;
import java.util.List;

public class CollegeManagementSystem {
    private List<Student> students;
    private List<Course> courses;
    private List<Faculty> faculties;

    public CollegeManagementSystem() {
        this.students = new ArrayList<>();
        this.courses = new ArrayList<>();
        this.faculties = new ArrayList<>();
    }

    public void addStudent(Student student) {
        students.add(student);
    }

    public void addCourse(Course course) {
        courses.add(course);
    }

    public void addFaculty(Faculty faculty) {
        faculties.add(faculty);
    }

    public List<Student> getStudents() {
        return students;
    }

    public List<Course> getCourses() {
        return courses;
    }

    public List<Faculty> getFaculties() {
        return faculties;
    }

    // Additional management methods can be added here
}
