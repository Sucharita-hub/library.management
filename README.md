# library.management

class Book {
    public void checkOut() {
        System.out.println("Checking out");
    }
    public void returnBook() {
        System.out.println("Return the book");
    }
    public void catalog() {
        System.out.println("Catalog");
    }
}

public class Main {
    public static void main(String[] args) {
        Book book1 = new Book();
        manageBook(book1);
        Book book2 = new Book();
        manageBook(book2);
    }
    
    public static void manageBook(Book book) {
        book.checkOut();
        book.returnBook();
        book.catalog();
    }
}
