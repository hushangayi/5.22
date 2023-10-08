# 5.22
import java.util.Date;
  
public class DateDemo {
 
   public static void main(String[] args) {
       // 初始化 Date 对象
       Date date = new Date();
        
       // 显示格式化时间
       System.out.printf("%s %tB %<te, %<tY", 
                         "Due date:", date);
   }
}
