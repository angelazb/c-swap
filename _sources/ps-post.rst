Post Test
-----------------------------------------------------

Please answer
the following problems to the best of your ability without any
outside help. You can stop working on a problem after you worked
on it for about five minutes without solving it.

Problems
==============

.. activecode:: cs-swap1-ac-v1
   :language: c

   Finish writing the code to swap the values in x and y (so that x ends up with y's initial value and y ends up with x's initial value).
   ~~~~

   #include <stdio.h>

   int main() {
      char x = 'm';
      char y = 'n';
      char temp;

      // print the values
      printf("x is %c\n", x);
      printf("y is %c\n", y);

      // swap the values of x and y
      // write your code here

      // print the values
      printf("x is %c\n", x);
      printf("y is %c\n", y);

      return 0;
   }

.. activecode:: cs-swap2-ac-v1
   :language: c

   Finish writing the code to swap the string values in a and b (so that a ends up with b’s initial string value and b ends up with a’s initial string value).
   ~~~~

   #include <stdio.h>

   int main() {
      char a[1024] = "This is a longer string";
      char b[1024] = "Short";
      char temp[1024];

      // print the values
      printf("a is %s\n", a);
      printf("b is %s\n", b);

      // swap the values of a and b
      // write your code here

      // print the values
      printf("a is %s\n", a);
      printf("b is %s\n", b);

      return 0;
   }


Feedback
==================================

.. shortanswer:: ps-posttest-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.

Thank You
============================
Thank you for taking part in this study!  We appreciate your time on this.
