public class StringPractice {
    public static void main(String[] args) {

        String str1 = "Hello";
        String str2 = "World";

        // 1. length()
        System.out.println("Length of str1: " + str1.length());

        // 2. concat()
        System.out.println("Concatenation: " + str1.concat(" " + str2));

        // 3. toUpperCase()
        System.out.println("Uppercase: " + str1.toUpperCase());

        // 4. toLowerCase()
        System.out.println("Lowercase: " + str2.toLowerCase());

        // 5. substring()
        System.out.println("Substring of str1: " + str1.substring(1, 4));

        // 6. equals()
        System.out.println("Are strings equal? " + str1.equals(str2));

        // 7. replace()
        System.out.println("Replace l with x: " + str1.replace('l', 'x'));

        // 8. charAt()
        System.out.println("Character at index 2: " + str1.charAt(2));
    }
}
