import java.util.Scanner;
//任务需求：打印出任何数一个范围的所有数字综合以及奇偶数
public class TextEventing {
    public static void main(String[] args) {
//        输入参数
        int a;
        int math = 0;
        int event = 0;
        int add = 0;
        Scanner sc = new Scanner(System.in);
//        打印输出的字符
        System.out.println("请输入字符串:");
//        控制台进行接收
        a = sc.nextInt();
//        math = a;
        System.out.println("a=" + math);
//        System.out.println("你输入的字符串为；"+a);

            for (event = a; event < 100;event++) {
//                event += 1;
                System.out.println("参数:" + event);
                if (event % 2 == 0) {
//                    add+=1;
                    System.out.println("a小于100时的所有的偶数为:" + event);
                } else {
                    System.out.println("a小于100时的所有的偶数为:" + add);
                }

            }

        }
    }












