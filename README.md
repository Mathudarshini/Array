
public class Main {
    public static void main(String[] args) {
        // 1D Array
        int[] arr1D = {1, 2, 3, 4, 5};
        System.out.println("1D Array:");
        for (int i = 0; i < arr1D.length; i++) {
            System.out.print(arr1D[i] + " ");
        }
        System.out.println();

        // 2D Array
        int[][] arr2D = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};
        System.out.println("2D Array:");
        for (int i = 0; i < arr2D.length; i++) {
            for (int j = 0; j < arr2D[i].length; j++) {
                System.out.print(arr2D[i][j] + " ");
            }
            System.out.println();
        }

        // 3D Array
        int[][][] arr3D = {{{1, 2, 3}, {4, 5, 6}}, {{7, 8, 9}, {10, 11, 12}}};
        System.out.println("3D Array:");
        for (int i = 0; i < arr3D.length; i++) {
            for (int j = 0; j < arr3D[i].length; j++) {
                for (int k = 0; k < arr3D[i][j].length; k++) {
                    System.out.print(arr3D[i][j][k] + " ");
                }
                System.out.println();
            }
            System.out.println();
        }

        // 4D Array
        int[][][][] arr4D = {{{{1, 2, 3}, {4, 5, 6}}, {{7, 8, 9}, {10, 11, 12}}}, {{{13, 14, 15}, {16, 17, 18}}, {{19, 20, 21}, {22, 23, 24}}}};
        System.out.println("4D Array:");
        for (int i = 0; i < arr4D.length; i++) {
            for (int j = 0; j < arr4D[i].length; j++) {
                for (int k = 0; k < arr4D[i][j].length; k++) {
                    for (int l = 0; l < arr4D[i][j][k].length; l++) {
                        System.out.print(arr4D[i][j][k][l] + " ");
                    }
                    System.out.println();
                }
                System.out.println();
            }
            System.out.println();
        }
    }
}


Output:

1D Array:
1 2 3 4 5
2D Array:
1 2 3
4 5 6
7 8 9
3D Array:
1 2 3
4 5 6

7 8 9
10 11 12

4D Array:
1 2 3
4 5 6

7 8 9
10 11 12

13 14 15
16 17 18

19 20 21
22 23 24# Array
