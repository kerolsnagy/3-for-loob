# 3-for-loob
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        for (int i = 1; i <= 2; i++)
        {
            System.out.println("Outer loop #1# i" + i);
            for (int j = 1; j <= 3; j++)
                System.out.println("Nested loop #2# j" + j);
               for (int k = 1; k <= 2; k++)
                    System.out.println("Nested loop #3# k" + k);
        }
        System.out.println("continue");

    }
}
