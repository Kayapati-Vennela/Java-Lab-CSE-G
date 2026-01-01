# experiment 2
## TITLE :  2a.) IMPLEMENTING A MECHANISM IN JAVA
```
class Rectangle{
        double length;
        double breadth;
        double area(){
                return length*breadth;}
        double perimeter(){
                return 2*(length+breadth);}
}
class main{
        public static void main(String args[]){
                Rectangle rect =new Rectangle();
                rect.length=10;
                rect.breadth=5;
                double area=rect.area();
                double perimeter=rect.perimeter();
                System.out.println("area:" + area);
                System.out.println("peri:" +perimeter);
        }
}
```
## output 
![output for mechanism in java]()
