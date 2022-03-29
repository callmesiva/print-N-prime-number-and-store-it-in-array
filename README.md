# print-N-prime-number-and-store-it-in-array

       int n = 15;
       int k=0;
       int counter= 0;
       
       int arr[] = new  int[n];
       
       for(int i=2; i<1000; i++)
       {
         if(i==2 || i==3 || i==5 || i==7 || i%2!=0 && i%3!=0 && i%5!=0 && i%7!=0)
         {
           arr[k]=i;
           k++;
           counter++;
           
          }
          
          if(counter==n)
          {
            break;
          }
      }
      
      
      for(int i=0; i<arr.length; i++)
      {
        System.out.println(arr[i]);
      }
