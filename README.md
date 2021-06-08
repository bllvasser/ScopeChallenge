# ScopeChallenge
package com.bilaal;

import java.util.Scanner;

public class X {
    private int x;

    private Scanner scanner = new Scanner(System.in);

    public X() {

    }

    public void timeTable() {

        System.out.println("Enter number: ");
        x = scanner.nextInt();
        for (int x = 1; x <= 12; x++) {
            System.out.println(this.x + " times " + x + " = " + this.x * x);
        }

    }
}
package com.bilaal;

public class Main {

   private static X x = new X();

    public static void main(String[] args) {
        X x = new X();

        x.timeTable();

    }
}
