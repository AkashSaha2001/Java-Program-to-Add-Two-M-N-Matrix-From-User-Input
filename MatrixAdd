import java.util.*;

public class MatrixAdd
{
    public static void main(String args[])
    {

//First Matrix

        Scanner sc=new Scanner(System.in);
        System.out.println("Enetr the row of your first matrix:");
        int row1=sc.nextInt();
        System.out.println("Enetr the col of your first matrix:");
        int col1=sc.nextInt();

        int[][] matrix1= new int[row1][col1];

        //input
        System.out.println("Enetr your first Matrix:");
        for(int i=0;i<row1;i++)
        {
            for(int j=0;j<col1;j++)
            {
                matrix1[i][j]=sc.nextInt();
            }
        }
        //output
        System.out.println("Your first Matrix is:");
        for(int i=0;i<row1;i++)
        {
            for(int j=0;j<col1;j++)
            {
                System.out.print(" "+matrix1[i][j]);
            }
            System.out.println();
        }

// Second Matrix

        System.out.println("Enetr the row of your second matrix:");
        int row2=sc.nextInt();
        System.out.println("Enetr the col of your second matrix:");
        int col2=sc.nextInt();

        int[][] matrix2= new int[row1][col1];

        //input
        System.out.println("Enetr your second Matrix:");
        for(int i=0;i<row2;i++)
        {
            for(int j=0;j<col2;j++)
            {
                matrix2[i][j]=sc.nextInt();
            }
        }
        //output
        System.out.println("Your second Matrix is:");
        for(int i=0;i<row2;i++)
        {
            for(int j=0;j<col2;j++)
            {
                System.out.print(" "+matrix2[i][j]);
            }
            System.out.println();
        }

         
// Matrix Addition


        //input
         int[][] matrix3= new int[row1][col2];

         for (int i = 0; i < row1; i++) 
         {
             for (int j = 0; j < col1; j++) 
             {
                matrix3[i][j] = matrix1[i][j] + matrix2[i][j];
                 
             }
         }
         //output
         System.out.println("Matrix after addition:");
         for (int i = 0; i < row1; i++) 
         {
             for (int j = 0; j < col2; j++) 
             {
                 System.out.print(matrix3[i][j]+"  ");
             }
             System.out.println();
         }
    }
}
