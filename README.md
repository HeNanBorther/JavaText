import java.util.Scanner;
#任务需求：打印出任何数一个范围的所有数字综合以及奇偶数
public class TextEventing {
    public static void main(String[] args) {
#        输入参数
        int a;
        int math = 0;
        int event = 0;
        int add = 0;
        Scanner sc = new Scanner(System.in);
#        打印输出的字符
        System.out.println("请输入字符串:");
#       控制台进行接收
        a = sc.nextInt();
#        math = a;
        System.out.println("a=" + math);
#        System.out.println("你输入的字符串为；"+a);

            for (event = a; event < 100;event++) {
#                event += 1;
                System.out.println("参数:" + event);
                if (event % 2 == 0) {
#                    add+=1;
                    System.out.println("a小于100时的所有的偶数为:" + event);
                } else {
                    System.out.println("a小于100时的所有的偶数为:" + add);
                }

            }

        }
    }
    import jdk.swing.interop.SwingInterOpUtils;

public class XunHuanText {
    public static void main(String[] args) {


        
       # 在嵌套循环for语句中，注意print与println之间的打印支付或数据的差异在47-49行，有所体现
       #  print 打印出的数据或者是字符为横向打印
       # println  打印出来的数据或者是字符为纵向打印
        
        






#      循环嵌套:循环语句内部，再写一个循环或则多个循环，成为循环嵌套。最多见的就是量程嵌套
#        定义初始值
        int a=0;
        int i=0;
        for(i=0;i<5;i++){
            for(a=0;a<5;a++){
                System.out.print(i+" "+"\t");
        }
            System.out.println();
        }


#       打印乘法表
        int a=1;
        int b=1;
        for(b=1;b<9;b++){
            for (a=1;a<=b;a++){
                System.out.print(b+"*"+a+"="+(a*b)+"\t");
            }
            System.out.println();
        }

#定义一个简单变量符号
        int a;
        int b;
        for(b=0;b<5;b++){
            for(a=0;a<5;a++){
                System.out.print(a+"\t");
                System.out.print(b+"\t");
#       print 打印出的数据或者是字符为横向打印
#        println  打印出来的数据或者是字符为纵向打印
            }
            System.out.println("\r");
        }*/


#
#打印5*5星号

#        定义俩数据a，b
        int q;
        int w;
        for(q=0;q<5;q++){
            for (w=0;w<5;w++){
                System.out.print("*"+"\t");
            }
            System.out.println("\r");
        }




#使用嵌套循环，打印5*5的方阵
        int count =0;
    for(int m=1;m<=5;m++){
        for(int i=0;i<5;i++ ){
            if((m+i)%2==1){
                System.out.print("*\t");
            }else{
                System.out.print("#\t");
            }
        }
        System.out.println("\t");

}



#       打印    嵌套循环跳转(打印101-150之间的所有质数)
        int a;
        int b;
        for(a=101;a<150;a++){
            for(b=2;b<a/2;b++){
                if(a/b==0){
                    continue;
#                  符合条件，跳到外部循环继续
                }

            }
            System.out.print(a+" ");
        }
 }
}

















