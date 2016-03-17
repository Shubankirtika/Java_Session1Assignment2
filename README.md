# Prime-numbers-1to100-using-for-and-break
class Prime1to100
{
  public static void main(String args[])
  {
    int i,j,k;
    System.out.println("Prime nubers between 1 and 100);
    for(i=1;i<100;i++)
    {
      k=0;
      for(j=2;j<i;j++)
      {
        if(i%j==0)
        {
          k==1;
          break;
        }
      }
      if(k==0)
      {
        System.out.print(" "+i);
      }
    }
  }
}
    
