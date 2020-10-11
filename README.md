public class Lab4 {

    public static void main(String[] args) {
        TestThread nur =new TestThread();
        nur.start();
        
    }
    
}
class TestThread extends Thread{
    @Override
    public void run(){
        for(int i=0;i<1000;i++){
            System.out.println(this.getName()+" "+i);
           
            }
        }
    }
