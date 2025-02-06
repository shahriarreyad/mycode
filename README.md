class Meta {
    private int userId;
    private String email;
    private String name;
    private int age;

    public Meta(int userId, String email, String name, int age) {
        this.userId = userId;
        this.email = email;
        this.name = name;
        this.age = age;
    }

    public void setUserId(int userId) {
        this.userId = userId;
    }

    public void setEmail(String email) {
        this.email = email;
    }

    public void setName(String name) {
        this.name = name;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public int getUserId() {
        return userId;
    }

    public String getEmail() {
        return email;
    }

    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }
}

public class Main {
    public static void main(String[] args) {
        Meta facebook = new Meta(23215691, "rahatshahriarreyad@gmail.com", "Rahat Shahriar Reyad", 22);

        System.out.println("User ID: " + facebook.getUserId());
        System.out.println("Email: " + facebook.getEmail());
        System.out.println("Name: " + facebook.getName());
        System.out.println("Age: " + facebook.getAge());
    }
}
