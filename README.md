/*
  вывод аргументов командной строки в консоль
*/
public class PrintArguments {
  public static void main(String[ ] args) {
    for (String str : args) {
      System.out.printf("Aргумент-> %s%n", str);
    }
    /*  // традиционный вид цикла for
    for (int i = 0; i < args.length; i++) {
      System.out.println("Aргумент-> " + args[i]);
    }
    */
  }
}
