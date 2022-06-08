he main() method of IterativeBinarySearch class starts off with defining a Array of size 6, named A.
Key is the number to be searched in the list of elements.
Inside the while loop, "mid" is obtained by calculating (low+high)/2.
If number at position mid equal to key or target element then the control returns index of mid element by printing that the number has been found along with the index at which it was found.
*Else, if key or target is less than number at position mid then the portion of the Array from the mid upwards is removed from contention by making "high" equal to mid-1.
Else, it implies that key element is greater than number at position mid(as it is not less than and also not equal, hence, it has to be greater). Hence, the portion of the list from mid and downwards is removed from contention by making "low" equal to mid+1.
The while loop continues to iterate in this way till either the element is returned (indicating key has been found in the Array) or low becomes greater than high,in which case -1 is returned indicating that key could not be found and the same is printed as output.
