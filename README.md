# Thread-Class
Creating thread using thread class
import java.io.*;
class GFG extends Thread {
    public void run()
    {
        System.out.print("Welcome to GeeksforGeeks.");
    }
    public static void main(String[] args)
    {
        GFG g = new GFG(); // creating thread
        g.start(); // starting thread
    }
}
