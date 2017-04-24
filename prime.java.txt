public class Find10prime {


      public Find10prime() { 

            // TODO Auto-generated constructor stub 

      } 

      public static void main(String[] args) { 

            // TODO Auto-generated method stub 

            int num=10; 

            int m=0,i; 

            for( i=2;i<=num;i++) 

            { 

                   for(int j=2;j<i;j++){ 

                         if(i%j==0) 

                        { 

                              m=1; 

                              break; 

                        } 

                         else{ 

                               m=0; 

                         } 

                        

                    } 

            

            if(m==0){ 

                  System.out.println(i); 

             } 

        }


      }


}