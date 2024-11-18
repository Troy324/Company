# Company
class Company {
// Поля класса
private String name;
    private int yearFounded;
// Конструктор класса
public Company(String name, int yearFounded) {
    this.name = name;
    this.yearFounded = yearFounded;    }
    // Метод для получения информации о компании
    public String getInfo() {
        return "Компания: " + name + ", Год основания: " + yearFounded;
    }}
public class Main {
    public static void main(String[] args) {
        // Создание объекта класса Company
        Company company1 = new Company("Tech Innovations", 2010);
        // Вывод информации о компании
        System.out.println(company1.getInfo());
    }}
