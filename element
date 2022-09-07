import java.util.*;
class elements{
   public
    String products;
    int price,gst,quantity;
    int total=0;
}
class Main extends elements{
    public static void main(String[] args) {
        elements [] a = new elements[10];
        int z,l=0;
        Scanner sc= new Scanner(System.in);
        System.out.println("Enter number of elements");
        z= sc.nextInt();
        int k=0;
        int max;
        for(int i=1;i<=z;i++)
        {
            a[i].products= sc.next();
            a[i].price=sc.nextInt();
            a[i].gst=sc.nextInt();
            a[i].quantity=sc.nextInt();
            a[i].total=(((a[i].gst*100)/a[i].price)+a[i].price)*a[i].gst;
        }
        max=a[0].gst;
        l=a[0].total;
        for(int i=1 ;i<z;i++)
        {
            if(max<a[i].gst)
            {
              k=i; 
              max=a[i].gst;
            }
            l=l+a[i].total;
        }
        System.out.println("Product Having max gst is "+a[k].products);
        System.out.println("Total Amout has to be paid "+l);
    }
}
