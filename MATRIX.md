#include<iostream>
using namespace std;
	int main(){
		int matrix [ 2 ][ 3 ], row , col , maxrows = 2 , maxcols = 3;
		
		// Get Values for the matrix 
		for ( row = 0; row < maxrows; row++ ){
			for ( col = 0; col < maxcols; col++ ){
				cout << " Please Enter a Value for position [ " << row << " , " << col << " ] ";
				cin >> matrix [ row ] [ col ];
			}
		}
		// Display The Values of Matrix 
		cout << " The Values Entered for the matrix are " << '\n';
		for ( row = 0; row < maxrows; row ++ ){
			for ( col = 0; col < maxcols; col++ ){
				cout << "\t" << matrix [ row ][ col];
			}
			cout << endl;
		} 
	}
