#include<iostream>
using namespace std;
	int main() {
		int k,q,w;
		int arr[10][10];
		k = 100;
		q = 100;
		for (int i = 0; i < 10; ++i) {
			for (int j = 0; j < 10; ++j) {
				if (i % 2 == 0) {
					arr[i][j] = k;
					k--;
				}
				else {
					arr[i][j] = k;
					k++;
				}
			}
     if (i % 2 == 0) {
       w = (k - 9);
				k = w;
			}
			else {
		 w = (k - 11);
		 k = w;
			}
		}
			}
