import javax.swing.JOptionPane;

public class RandomGuess {
    public static void main(String[] args) {
        // First dialog box asking the user to think of a number
        JOptionPane.showMessageDialog(null, "Think of a number between 1 and 10");

        // Generate a random number between 1 and 10
        int randomNumber = 1 + (int)(Math.random() * 10);

        // Second dialog box displaying the random number
        JOptionPane.showMessageDialog(null, "The number is " + randomNumber);
    }
}
