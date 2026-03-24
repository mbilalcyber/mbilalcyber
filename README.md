# Hi, I'm Muhammad Bilal 👋  

🎓 Business Administration & Cybersecurity Student  

I’m focused on building a strong foundation at the intersection of technology and business, with a growing interest in cybersecurity, networking, and real-world problem solving.

## 🚀 What I’m Working On  
- Developing practical skills in cybersecurity fundamentals & networking  
- Strengthening my understanding of business operations, sales, and management  
- Exploring how technology and business strategy connect in real-world environments  

## 🧠 Skills & Tools  
- Programming: C++, Java (learning & improving)  
- Networking: Cisco Networking Basics, IP Configuration  
- Web: HTML, CSS (in progress)  
- Business & Marketing: SEO (On-Page & Off-Page), Keyword Research, Content Optimization  

## 💼 Experience & Interests  
- Experience in SEO & digital marketing (content strategy, optimization, link building)  
- Interested in cybersecurity, cloud security, and tech-driven business solutions  
- Exploring sales, communication, and client-facing roles  

## 📷 Beyond Tech  
I enjoy photography and content creation, combining creativity with digital skills.

## 📫 Let’s Connect  
- LinkedIn: https://www.linkedin.com/in/muhammad-bilal-628058382/  
- Email: mubila02@wsc.edu


import java.util.ArrayList;
import java.util.List;

public class Inventory {

    public static void main(String[] args) {

        // Create list
        List<Book> inventory = new ArrayList<>();

        // Total value
        double totalValue = 0.0;

        // Add books
        inventory.add(new Book("ABC 123", 9.99));
        inventory.add(new Book("Java for Dummies", 29.99));
        inventory.add(new Book("Very Expensive Book", 1234.56));

        // Header
        System.out.println("=================================");
        System.out.println("        Book Store Inventory");
        System.out.println("=================================");

        // Display books and calculate total
        for (Book book : inventory) {
            System.out.println(book);
            totalValue += book.getPrice();
        }

        System.out.println("---------------------------------");

        // Print total
        System.out.println("Total Inventory Value = $ " + String.format("%,.2f", totalValue));
    }
}